<Type Name="UserAssertion" FullName="Microsoft.Identity.Client.UserAssertion">
  <TypeSignature Language="C#" Value="public sealed class UserAssertion" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UserAssertion extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.UserAssertion" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UserAssertion" />
  <TypeSignature Language="F#" Value="type UserAssertion = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ユーザーの資格情報を表すアサーションを格納している資格情報の種類。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAssertion (string assertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string assertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.UserAssertion.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (assertion As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.UserAssertion : string -&gt; Microsoft.Identity.Client.UserAssertion" Usage="new Microsoft.Identity.Client.UserAssertion assertion" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="assertion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="assertion">ユーザーを示すのアサーションです。</param>
        <summary>
            アサーションで、オブジェクトを作成するコンス トラクターです。 このコンス トラクターは、アサーションは、JWT トークンを前提とフローの代わりに使用できます。 他のフロー assertionType とその他の構築を使用する必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAssertion (string assertion, string assertionType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string assertion, string assertionType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.UserAssertion.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (assertion As String, assertionType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.UserAssertion : string * string -&gt; Microsoft.Identity.Client.UserAssertion" Usage="new Microsoft.Identity.Client.UserAssertion (assertion, assertionType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="assertion" Type="System.String" />
        <Parameter Name="assertionType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="assertion">ユーザーを示すのアサーションです。</param>
        <param name="assertionType">ユーザーを表す、アサーションの型。</param>
        <summary>
            アサーションと assertionType 資格情報を作成するコンス トラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Assertion">
      <MemberSignature Language="C#" Value="public string Assertion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Assertion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.UserAssertion.Assertion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Assertion As String" />
      <MemberSignature Language="F#" Value="member this.Assertion : string" Usage="Microsoft.Identity.Client.UserAssertion.Assertion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.UserAssertion.AssertionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AssertionType As String" />
      <MemberSignature Language="F#" Value="member this.AssertionType : string" Usage="Microsoft.Identity.Client.UserAssertion.AssertionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
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
  </Members>
</Type>