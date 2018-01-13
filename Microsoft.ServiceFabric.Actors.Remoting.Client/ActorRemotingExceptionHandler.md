<Type Name="ActorRemotingExceptionHandler" FullName="Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler">
  <TypeSignature Language="C#" Value="public class ActorRemotingExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorRemotingExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorRemotingExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type ActorRemotingExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            このクラスは、リモート アクター インターフェイス経由での service fabric アクターと通信中に発生した例外の処理を提供します。
            </summary>
    <remarks>
      <para>
                この例外ハンドラーは、次のシナリオに関連する例外を処理します。
            </para>
      <list type="list">
        <item>
          <term>
                重複するメッセージ。
            </term>
          <description>
            <para>
                例外処理のロジックに基づくクライアントからアクターに対して実行される操作が再試行されます。 これらの例外は、サービスのフェールオーバーを含むさまざまなエラー状態を表します。 したがって、アクターが重複するメッセージを受信することです。 アクターによって前のメッセージの処理中に重複するメッセージを受信する場合、ランタイムは、クライアントに内部例外を返します。 クライアントは、アクターから結果を戻すために、操作を再試行します。 クライアントがアクターの観点から重複する操作が実行され、操作は既に処理されて、し、重複するメッセージが到着した場合と同様の方法で処理が必要です。 
                </para>
            <para>
                返すことによって処理されている重複した操作に関連する例外が処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。
                <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />設定を true に、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。
                </para>
          </description>
        </item>
        <item>
          <term>
            <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />:
            </term>
          <description>
            <para>
                アクターの操作は、基にする同時実行のロックを使用して実行されます (<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />) 論理呼び出しコンテキスト ベースの再入をサポートします。 実行時間の長いアクター操作した場合は、このロックはタイムアウトが発生するの買収可能性があります。ロックの取得こともできます (アクター A および B が互いを同時にほぼ呼び出してアクター) に、デッドロックが発生した場合はタイムアウトが発生します。 
                </para>
            <para>
                同時実行のロックのタイムアウトに関連する例外を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッド操作を実行するクライアントが別のアクターにない場合。
                <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />設定を true に、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。
                </para>
            <para>
                同時実行のロックのタイムアウトに関連する例外を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッド、操作を実行するクライアントが別のアクターの場合。 これにより、呼び出しチェーンまでアンワインドするデッドロック状態では、元のクライアントにバックアップし、そこから、操作が再試行します。
                </para>
          </description>
        </item>
      </list>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorRemotingExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
                新しいインスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />リモート アクター インターフェイス経由での service fabric アクターと通信中に発生した例外の処理に使用できます。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="result" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="exceptionInformation">例外に関する情報</param>
        <param name="retrySettings">操作の再試行の設定。</param>
        <param name="result">例外処理の結果</param>
        <summary>
            例外を調査し、その例外を処理する方法を判断するメソッドです。 
            </summary>
        <returns>true の場合は、例外処理、それ以外の場合</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>