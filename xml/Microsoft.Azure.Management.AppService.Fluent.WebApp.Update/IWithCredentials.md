<Type Name="IWithCredentials" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials">
  <TypeSignature Language="C#" Value="public interface IWithCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCredentials" />
  <TypeSignature Language="F#" Value="type IWithCredentials = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5aed0-101">Web アプリは、docker hub の資格情報を設定するにすることができますを更新します。</span><span class="sxs-lookup"><span data-stu-id="5aed0-101">A web app update allowing docker hub credentials to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand WithCredentials (string username, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand WithCredentials(string username, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials.WithCredentials(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCredentials (username As String, password As String) As IWithStartUpCommand" />
      <MemberSignature Language="F#" Value="abstract member WithCredentials : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand" Usage="iWithCredentials.WithCredentials (username, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="username"><span data-ttu-id="5aed0-102">Docker Hub のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="5aed0-102">The username for Docker Hub.</span></span></param>
        <param name="password"><span data-ttu-id="5aed0-103">Docker Hub のパスワード。</span><span class="sxs-lookup"><span data-stu-id="5aed0-103">The password for Docker Hub.</span></span></param>
        <summary>
            <span data-ttu-id="5aed0-104">Docker Hub のユーザー名とパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="5aed0-104">Specifies the username and password for Docker Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5aed0-105">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5aed0-105">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>