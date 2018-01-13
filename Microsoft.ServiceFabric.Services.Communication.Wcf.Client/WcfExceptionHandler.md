<Type Name="WcfExceptionHandler" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler">
  <TypeSignature Language="C#" Value="public class WcfExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type WcfExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
            このクラスは、WCF を使用している service fabric サービスと通信中に発生した WCF 例外の処理はベースの通信リスナーを提供します。
            </summary>
    <remarks>
            以下の説明に従って、例外の処理: <list type="table"> <item> <description>次の例外は、サービスのフェールオーバーを指定します。これらの例外を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />を false に設定されている、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。<list type="bullet"><item><description><see cref="T:System.ServiceModel.EndpointNotFoundException" /></description></item><item><description><see cref="T:System.ServiceModel.CommunicationObjectAbortedException" /></description></item><item><description><see cref="T:System.ServiceModel.CommunicationObjectFaultedException" /></description></item><item><description><see cref="T:System.ObjectDisposedException" /></description></item><item><description><see cref="T:System.ServiceModel.ChannelTerminatedException" /></description></item></list></description></item><item><description>次の例外が一時的なエラー状態が示されを返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />設定を true に、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。<list type="bullet"><item><description><see cref="T:System.TimeoutException" /></description></item><item><description><see cref="T:System.ServiceModel.ServerTooBusyException" /></description></item></list></description></item><item><description>次の例外では、バインディングまたはコントラクト、クライアントとサービス間で不一致を示しています。これらの例外を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。<list type="bullet"><item><description><see cref="T:System.ServiceModel.ActionNotSupportedException" /></description></item><item><description><see cref="T:System.ServiceModel.AddressAccessDeniedException" /></description></item><item><description><see cref="T:System.ServiceModel.Security.SecurityAccessDeniedException" /></description></item></list></description></item><item><description>次の例外は、サービスからエラーを示すためです。返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。<list type="bullet"><item><description><see cref="T:System.ServiceModel.FaultException" /></description></item></list></description></item><item><description>その他のすべての例外<see cref="T:System.ServiceModel.CommunicationException" />、ではなく<see cref="T:System.ServiceModel.FaultException" />を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />設定を true に、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.DefaultMaxRetryCount" />です。</description></item></list></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            WcfExceptionHandler クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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