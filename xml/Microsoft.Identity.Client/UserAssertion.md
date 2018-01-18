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
            <span data-ttu-id="edb01-101">ユーザーの資格情報を表すアサーションを格納している資格情報の種類。</span><span class="sxs-lookup"><span data-stu-id="edb01-101">Credential type containing an assertion representing user credential.</span></span>
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
        <param name="assertion"><span data-ttu-id="edb01-102">ユーザーを示すのアサーションです。</span><span class="sxs-lookup"><span data-stu-id="edb01-102">Assertion representing the user.</span></span></param>
        <summary>
            <span data-ttu-id="edb01-103">アサーションで、オブジェクトを作成するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="edb01-103">Constructor to create the object with an assertion.</span></span> <span data-ttu-id="edb01-104">このコンス トラクターは、アサーションは、JWT トークンを前提とフローの代わりに使用できます。</span><span class="sxs-lookup"><span data-stu-id="edb01-104">This constructor can be used for On Behalf Of flow which assumes the assertion is a JWT token.</span></span> <span data-ttu-id="edb01-105">他のフロー assertionType とその他の構築を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="edb01-105">For other flows, the other construction with assertionType must be used.</span></span>
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
        <param name="assertion"><span data-ttu-id="edb01-106">ユーザーを示すのアサーションです。</span><span class="sxs-lookup"><span data-stu-id="edb01-106">Assertion representing the user.</span></span></param>
        <param name="assertionType"><span data-ttu-id="edb01-107">ユーザーを表す、アサーションの型。</span><span class="sxs-lookup"><span data-stu-id="edb01-107">Type of the assertion representing the user.</span></span></param>
        <summary>
            <span data-ttu-id="edb01-108">アサーションと assertionType 資格情報を作成するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="edb01-108">Constructor to create credential with assertion and assertionType</span></span>
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
            <span data-ttu-id="edb01-109">アサーションを取得します。</span><span class="sxs-lookup"><span data-stu-id="edb01-109">Gets the assertion.</span></span>
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
            <span data-ttu-id="edb01-110">アサーションの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="edb01-110">Gets the assertion type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>