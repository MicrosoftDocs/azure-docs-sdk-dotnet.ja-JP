<Type Name="IPrincipalExtensions" FullName="System.Security.Principal.IPrincipalExtensions">
  <TypeSignature Language="C#" Value="public static class IPrincipalExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IPrincipalExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Security.Principal.IPrincipalExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IPrincipalExtensions" />
  <TypeSignature Language="F#" Value="type IPrincipalExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAppServiceIdentityAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;T&gt; GetAppServiceIdentityAsync&lt;T&gt; (this System.Security.Principal.IPrincipal principal, System.Net.Http.HttpRequestMessage request) where T : Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentialsnew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;!!T&gt; GetAppServiceIdentityAsync&lt;.ctor (class Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials) T&gt;(class System.Security.Principal.IPrincipal principal, class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Security.Principal.IPrincipalExtensions.GetAppServiceIdentityAsync``1(System.Security.Principal.IPrincipal,System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAppServiceIdentityAsync(Of T As {ProviderCredentialsNew}) (principal As IPrincipal, request As HttpRequestMessage) As Task(Of T)" />
      <MemberSignature Language="F#" Value="static member GetAppServiceIdentityAsync : System.Security.Principal.IPrincipal * System.Net.Http.HttpRequestMessage -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials and 'T : (new : unit -&gt; 'T))" Usage="System.Security.Principal.IPrincipalExtensions.GetAppServiceIdentityAsync (principal, request)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="principal" Type="System.Security.Principal.IPrincipal" RefType="this" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
      </Parameters>
      <Docs>
        <typeparam name="T">プロバイダーの種類 </typeparam>
        <param name="principal"><see cref="T:System.Security.Principal.IPrincipal" /> オブジェクト。</param>
        <param name="request">要求コンテキスト。</param>
        <summary>
            特定の id の詳細を id プロバイダーを取得、<see cref="T:System.Security.Principal.IPrincipal" />要求を行います。
            </summary>
        <returns>Id プロバイダーの資格情報が存在すると、それ以外の場合に null の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppServiceIdentityAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;T&gt; GetAppServiceIdentityAsync&lt;T&gt; (this System.Security.Principal.IPrincipal principal, System.Net.Http.HttpRequestMessage request, System.Net.Http.HttpClient httpClient) where T : Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentialsnew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;!!T&gt; GetAppServiceIdentityAsync&lt;.ctor (class Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials) T&gt;(class System.Security.Principal.IPrincipal principal, class System.Net.Http.HttpRequestMessage request, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Security.Principal.IPrincipalExtensions.GetAppServiceIdentityAsync``1(System.Security.Principal.IPrincipal,System.Net.Http.HttpRequestMessage,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="static member GetAppServiceIdentityAsync : System.Security.Principal.IPrincipal * System.Net.Http.HttpRequestMessage * System.Net.Http.HttpClient -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials and 'T : (new : unit -&gt; 'T))" Usage="System.Security.Principal.IPrincipalExtensions.GetAppServiceIdentityAsync (principal, request, httpClient)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Security.Principal.IPrincipalExtensions/&lt;GetAppServiceIdentityAsync&gt;d__4`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="principal" Type="System.Security.Principal.IPrincipal" RefType="this" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="principal">To be added.</param>
        <param name="request">To be added.</param>
        <param name="httpClient">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>