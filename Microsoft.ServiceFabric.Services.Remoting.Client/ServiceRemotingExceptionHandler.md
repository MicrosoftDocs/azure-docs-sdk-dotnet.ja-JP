<Type Name="ServiceRemotingExceptionHandler" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler">
  <TypeSignature Language="C#" Value="public class ServiceRemotingExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type ServiceRemotingExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
            リモート インターフェイス上の service fabric サービスと通信中に発生した例外の処理を提供します。 
            </summary>
    <remarks>
            以下の説明に従って、例外の処理: <list type="table"> <item> <description>次の例外は、サービスのフェールオーバーを指定します。これらの例外を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />を false に設定されている、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。<list type="bullet"> <item> <description><see cref="T:System.Fabric.FabricNotPrimaryException" />ターゲット レプリカの場合、<see cref="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />です。</description></item><item><description><see cref="T:System.Fabric.FabricNotReadableException" /></description></item></list></description></item><item><description>次の例外が一時的なエラー状態が示されを返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />設定を true に、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。<list type="bullet"><item><description><see cref="T:System.Fabric.FabricTransientException" /></description></item></list></description></item></list></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            コンス トラクター、既定値 ServiceRemotingExceptionHandler トレース id。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingExceptionHandler (string traceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (traceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler : string -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler traceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="traceId">
                このコンポーネントからのトレースを診断で使用する ID です。
            </param>
        <summary>
            指定したトレース ID を持つ ServiceRemotingExceptionHandler を構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
        <param name="exceptionInformation">例外に関する情報。</param>
        <param name="retrySettings">操作の再試行の設定。</param>
        <param name="result">例外処理の結果。</param>
        <summary>
            例外を調査し、その例外の処理方法を決定します。 
            </summary>
        <returns>例外が処理された場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>