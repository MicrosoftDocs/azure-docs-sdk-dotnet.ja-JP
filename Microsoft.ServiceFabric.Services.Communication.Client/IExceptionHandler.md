<Type Name="IExceptionHandler" FullName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler">
  <TypeSignature Language="C#" Value="public interface IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExceptionHandler" />
  <TypeSignature Language="F#" Value="type IExceptionHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Service fabric サービスと通信中に発生した例外を処理するためのインターフェイスを定義します。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TryHandleException">
      <MemberSignature Language="C#" Value="public bool TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberSignature Language="F#" Value="abstract member TryHandleException : Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings *  -&gt; bool" Usage="iExceptionHandler.TryHandleException (exceptionInformation, retrySettings, result)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
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