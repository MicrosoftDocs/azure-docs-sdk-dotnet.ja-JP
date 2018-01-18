<Type Name="AdministratorDetails" FullName="Microsoft.Azure.KeyVault.Models.AdministratorDetails">
  <TypeSignature Language="C#" Value="public class AdministratorDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdministratorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.AdministratorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class AdministratorDetails" />
  <TypeSignature Language="F#" Value="type AdministratorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="77763-101">証明書の発行者の組織の管理者の詳細です。</span><span class="sxs-lookup"><span data-stu-id="77763-101">Details of the organization administrator of the certificate issuer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdministratorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.AdministratorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="77763-102">AdministratorDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77763-102">Initializes a new instance of the AdministratorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdministratorDetails (string firstName = null, string lastName = null, string emailAddress = null, string phone = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string firstName, string lastName, string emailAddress, string phone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.AdministratorDetails.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional firstName As String = null, Optional lastName As String = null, Optional emailAddress As String = null, Optional phone As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.AdministratorDetails : string * string * string * string -&gt; Microsoft.Azure.KeyVault.Models.AdministratorDetails" Usage="new Microsoft.Azure.KeyVault.Models.AdministratorDetails (firstName, lastName, emailAddress, phone)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="firstName" Type="System.String" />
        <Parameter Name="lastName" Type="System.String" />
        <Parameter Name="emailAddress" Type="System.String" />
        <Parameter Name="phone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firstName"><span data-ttu-id="77763-103">名。</span><span class="sxs-lookup"><span data-stu-id="77763-103">First name.</span></span></param>
        <param name="lastName"><span data-ttu-id="77763-104">姓。</span><span class="sxs-lookup"><span data-stu-id="77763-104">Last name.</span></span></param>
        <param name="emailAddress"><span data-ttu-id="77763-105">電子メール アドレス。</span><span class="sxs-lookup"><span data-stu-id="77763-105">Email addresss.</span></span></param>
        <param name="phone"><span data-ttu-id="77763-106">電話番号です。</span><span class="sxs-lookup"><span data-stu-id="77763-106">Phone number.</span></span></param>
        <summary>
            <span data-ttu-id="77763-107">AdministratorDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77763-107">Initializes a new instance of the AdministratorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAddress">
      <MemberSignature Language="C#" Value="public string EmailAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.AdministratorDetails.EmailAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAddress As String" />
      <MemberSignature Language="F#" Value="member this.EmailAddress : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.AdministratorDetails.EmailAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="email")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77763-108">取得または電子メール アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="77763-108">Gets or sets email addresss.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstName">
      <MemberSignature Language="C#" Value="public string FirstName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FirstName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.AdministratorDetails.FirstName" />
      <MemberSignature Language="VB.NET" Value="Public Property FirstName As String" />
      <MemberSignature Language="F#" Value="member this.FirstName : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.AdministratorDetails.FirstName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="first_name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77763-109">取得または姓を設定します。</span><span class="sxs-lookup"><span data-stu-id="77763-109">Gets or sets first name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastName">
      <MemberSignature Language="C#" Value="public string LastName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.AdministratorDetails.LastName" />
      <MemberSignature Language="VB.NET" Value="Public Property LastName As String" />
      <MemberSignature Language="F#" Value="member this.LastName : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.AdministratorDetails.LastName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="last_name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77763-110">取得または最後の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="77763-110">Gets or sets last name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Phone">
      <MemberSignature Language="C#" Value="public string Phone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Phone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.AdministratorDetails.Phone" />
      <MemberSignature Language="VB.NET" Value="Public Property Phone As String" />
      <MemberSignature Language="F#" Value="member this.Phone : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.AdministratorDetails.Phone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="phone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77763-111">取得または電話番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="77763-111">Gets or sets phone number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>