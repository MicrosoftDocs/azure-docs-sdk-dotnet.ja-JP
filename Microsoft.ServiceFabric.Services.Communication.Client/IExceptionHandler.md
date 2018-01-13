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
            <span data-ttu-id="b8b81-101">Service fabric サービスと通信中に発生した例外を処理するためのインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="b8b81-101">Defines the interface for handling the exceptions encountered in communicating with service fabric services.</span></span> 
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
        <param name="exceptionInformation"><span data-ttu-id="b8b81-102">例外に関する情報</span><span class="sxs-lookup"><span data-stu-id="b8b81-102">Information about the exception</span></span></param>
        <param name="retrySettings"><span data-ttu-id="b8b81-103">操作の再試行の設定。</span><span class="sxs-lookup"><span data-stu-id="b8b81-103">The operation retry preferences.</span></span></param>
        <param name="result"><span data-ttu-id="b8b81-104">例外処理の結果</span><span class="sxs-lookup"><span data-stu-id="b8b81-104">Result of the exception handling</span></span></param>
        <summary>
            <span data-ttu-id="b8b81-105">例外を調査し、その例外を処理する方法を判断するメソッドです。</span><span class="sxs-lookup"><span data-stu-id="b8b81-105">Method that examines the exception and determines how that exception can be handled.</span></span> 
            </summary>
        <returns><span data-ttu-id="b8b81-106">true の場合は、例外処理、それ以外の場合</span><span class="sxs-lookup"><span data-stu-id="b8b81-106">true if the exception is handled, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>