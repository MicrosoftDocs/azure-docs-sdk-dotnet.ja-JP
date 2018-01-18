<Type Name="IWithCredentials" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials">
  <TypeSignature Language="C#" Value="public interface IWithCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCredentials" />
  <TypeSignature Language="F#" Value="type IWithCredentials = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="07219-101">Docker を設定するレジストリの資格情報を許可する web アプリケーションの定義。</span><span class="sxs-lookup"><span data-stu-id="07219-101">A web app definition allowing docker registry credentials to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand WithCredentials (string username, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand WithCredentials(string username, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials.WithCredentials(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCredentials (username As String, password As String) As IWithStartUpCommand" />
      <MemberSignature Language="F#" Value="abstract member WithCredentials : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand" Usage="iWithCredentials.WithCredentials (username, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="username"><span data-ttu-id="07219-102">Docker Hub または docker のレジストリのユーザー名。</span><span class="sxs-lookup"><span data-stu-id="07219-102">The username for Docker Hub or the docker registry.</span></span></param>
        <param name="password"><span data-ttu-id="07219-103">Docker Hub または docker のレジストリのパスワード。</span><span class="sxs-lookup"><span data-stu-id="07219-103">The password for Docker Hub or the docker registry.</span></span></param>
        <summary>
            <span data-ttu-id="07219-104">Docker Hub または docker のレジストリのユーザー名とパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="07219-104">Specifies the username and password for Docker Hub or the docker registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="07219-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="07219-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>