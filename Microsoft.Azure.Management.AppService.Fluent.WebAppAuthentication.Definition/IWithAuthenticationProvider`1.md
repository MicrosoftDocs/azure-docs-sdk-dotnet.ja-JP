<Type Name="IWithAuthenticationProvider&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAuthenticationProvider&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthenticationProvider`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthenticationProvider(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAuthenticationProvider&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の定義の段階です。</typeparam>
    <summary>
            指定するプロバイダーの詳細な情報を許可する、web アプリの認証定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithActiveDirectory">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithActiveDirectory (string clientId, string issuerUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithActiveDirectory(string clientId, string issuerUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithActiveDirectory(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithActiveDirectory (clientId As String, issuerUrl As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithActiveDirectory : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithActiveDirectory (clientId, issuerUrl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="issuerUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId">AAD アプリのクライアントの id。</param>
        <param name="issuerUrl">Https://sts.windows.net/(テナント Id) の形式でトークン発行者の URL です。</param>
        <summary>
            Active Directory およびそのクライアント ID と発行者の URL であるプロバイダーを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithFacebook">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithFacebook (string appId, string appSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithFacebook(string appId, string appSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithFacebook(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFacebook (appId As String, appSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFacebook : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithFacebook (appId, appSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appId" Type="System.String" />
        <Parameter Name="appSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appId">Facebook アプリ id。</param>
        <param name="appSecret">Facebook アプリのシークレット。</param>
        <summary>
            Facebook アプリ ID およびそのアプリのシークレットをあるプロバイダーを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithGoogle">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithGoogle (string clientId, string clientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithGoogle(string clientId, string clientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithGoogle(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGoogle (clientId As String, clientSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGoogle : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithGoogle (clientId, clientSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId">Google のアプリのクライアント ID</param>
        <param name="clientSecret">Google のアプリのクライアント シークレット。</param>
        <summary>
            Google、クライアント ID、およびクライアント シークレットをあるプロバイダーを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithMicrosoft">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithMicrosoft (string clientId, string clientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithMicrosoft(string clientId, string clientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithMicrosoft(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMicrosoft (clientId As String, clientSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMicrosoft : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithMicrosoft (clientId, clientSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId">Microsoft アプリのクライアントの id。</param>
        <param name="clientSecret">Microsoft アプリのクライアント シークレット。</param>
        <summary>
            Microsoft およびそのクライアント ID およびクライアント シークレットをあるプロバイダーを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithTwitter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithTwitter (string apiKey, string apiSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithTwitter(string apiKey, string apiSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1.WithTwitter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTwitter (apiKey As String, apiSecret As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTwitter : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAuthenticationProvider.WithTwitter (apiKey, apiSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiKey" Type="System.String" />
        <Parameter Name="apiSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apiKey">Twitter アプリの API キー。</param>
        <param name="apiSecret">Twitter アプリの API のシークレット。</param>
        <summary>
            Twitter であるプロバイダーを指定します、API キー、および API シークレット。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>