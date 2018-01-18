<Type Name="IAuthenticationHandler" FullName="Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler">
  <TypeSignature Language="C#" Value="public interface IAuthenticationHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAuthenticationHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAuthenticationHandler" />
  <TypeSignature Language="F#" Value="type IAuthenticationHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b1b82-101">HTTP 要求に署名するハンドラーを表します。</span><span class="sxs-lookup"><span data-stu-id="b1b82-101">Represents a handler that signs HTTP requests.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="SignRequest">
      <MemberSignature Language="C#" Value="public void SignRequest (System.Net.HttpWebRequest request, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SignRequest(class System.Net.HttpWebRequest request, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="iAuthenticationHandler.SignRequest (request, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="b1b82-102">署名する HTTP 要求。</span><span class="sxs-lookup"><span data-stu-id="b1b82-102">The HTTP request to sign.</span></span></param>
        <param name="operationContext"><span data-ttu-id="b1b82-103"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b1b82-103">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="b1b82-104">記号、指定した HTTP では、Microsoft Azure ストレージ サービスで認証できるようにを要求します。</span><span class="sxs-lookup"><span data-stu-id="b1b82-104">Signs the specified HTTP request so it can be authenticated by the Microsoft Azure storage services.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>