<Type Name="ClientAssertion" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion">
  <TypeSignature Language="C#" Value="public sealed class ClientAssertion" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClientAssertion extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClientAssertion" />
  <TypeSignature Language="F#" Value="type ClientAssertion = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            資格情報の種類の型のアサーションを含む"urn: ietf:params:oauth:token-型: jwt"です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientAssertion (string clientId, string assertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string assertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, assertion As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion (clientId, assertion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="assertion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="assertion">資格情報として使用される jwt。</param>
        <summary>
            Base64 url でエンコードされた文字列としてエンコードされた jwt トークンを使用して資格情報を作成するコンス トラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Assertion">
      <MemberSignature Language="C#" Value="public string Assertion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Assertion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.Assertion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Assertion As String" />
      <MemberSignature Language="F#" Value="member this.Assertion : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.Assertion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アサーションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssertionType">
      <MemberSignature Language="C#" Value="public string AssertionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AssertionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.AssertionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AssertionType As String" />
      <MemberSignature Language="F#" Value="member this.AssertionType : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.AssertionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アサーションの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トークンを要求したクライアントの識別子を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>