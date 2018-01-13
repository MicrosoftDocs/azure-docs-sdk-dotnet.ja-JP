<Type Name="Contact" FullName="Microsoft.Azure.KeyVault.Models.Contact">
  <TypeSignature Language="C#" Value="public class Contact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Contact extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.Contact" />
  <TypeSignature Language="VB.NET" Value="Public Class Contact" />
  <TypeSignature Language="F#" Value="type Contact = class" />
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
            <span data-ttu-id="38d23-101">コンテナーの証明書の連絡先情報。</span><span class="sxs-lookup"><span data-stu-id="38d23-101">The contact information for the vault certificates.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Contact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Contact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="38d23-102">連絡先クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="38d23-102">Initializes a new instance of the Contact class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Contact (string emailAddress = null, string name = null, string phone = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string emailAddress, string name, string phone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Contact.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional emailAddress As String = null, Optional name As String = null, Optional phone As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.Contact : string * string * string -&gt; Microsoft.Azure.KeyVault.Models.Contact" Usage="new Microsoft.Azure.KeyVault.Models.Contact (emailAddress, name, phone)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="emailAddress" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="phone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="emailAddress"><span data-ttu-id="38d23-103">電子メール アドレス。</span><span class="sxs-lookup"><span data-stu-id="38d23-103">Email addresss.</span></span></param>
        <param name="name"><span data-ttu-id="38d23-104">名前。</span><span class="sxs-lookup"><span data-stu-id="38d23-104">Name.</span></span></param>
        <param name="phone"><span data-ttu-id="38d23-105">電話番号です。</span><span class="sxs-lookup"><span data-stu-id="38d23-105">Phone number.</span></span></param>
        <summary>
            <span data-ttu-id="38d23-106">連絡先クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="38d23-106">Initializes a new instance of the Contact class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAddress">
      <MemberSignature Language="C#" Value="public string EmailAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Contact.EmailAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAddress As String" />
      <MemberSignature Language="F#" Value="member this.EmailAddress : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.Contact.EmailAddress" />
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
            <span data-ttu-id="38d23-107">取得または電子メール アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="38d23-107">Gets or sets email addresss.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Contact.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.Contact.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38d23-108">取得または名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="38d23-108">Gets or sets name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Phone">
      <MemberSignature Language="C#" Value="public string Phone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Phone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Contact.Phone" />
      <MemberSignature Language="VB.NET" Value="Public Property Phone As String" />
      <MemberSignature Language="F#" Value="member this.Phone : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.Contact.Phone" />
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
            <span data-ttu-id="38d23-109">取得または電話番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="38d23-109">Gets or sets phone number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>