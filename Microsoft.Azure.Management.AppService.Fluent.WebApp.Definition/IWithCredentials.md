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
            Docker を設定するレジストリの資格情報を許可する web アプリケーションの定義。
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
        <param name="username">Docker Hub または docker のレジストリのユーザー名。</param>
        <param name="password">Docker Hub または docker のレジストリのパスワード。</param>
        <summary>
            Docker Hub または docker のレジストリのユーザー名とパスワードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>