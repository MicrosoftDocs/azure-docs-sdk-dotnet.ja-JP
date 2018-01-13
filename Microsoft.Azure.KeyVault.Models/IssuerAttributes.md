<Type Name="IssuerAttributes" FullName="Microsoft.Azure.KeyVault.Models.IssuerAttributes">
  <TypeSignature Language="C#" Value="public class IssuerAttributes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerAttributes extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerAttributes" />
  <TypeSignature Language="F#" Value="type IssuerAttributes = class" />
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
            <span data-ttu-id="ad03a-101">Key Vault サービスによって管理される発行元の属性。</span><span class="sxs-lookup"><span data-stu-id="ad03a-101">The attributes of an issuer managed by the Key Vault service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerAttributes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerAttributes.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ad03a-102">IssuerAttributes クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ad03a-102">Initializes a new instance of the IssuerAttributes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerAttributes (Nullable&lt;bool&gt; enabled = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; updated = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updated) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerAttributes.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional created As Nullable(Of DateTime) = null, Optional updated As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.IssuerAttributes : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.KeyVault.Models.IssuerAttributes" Usage="new Microsoft.Azure.KeyVault.Models.IssuerAttributes (enabled, created, updated)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updated" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="ad03a-103">発行者が有効になっているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="ad03a-103">Determines whether the issuer is enabled.</span></span></param>
        <param name="created"><span data-ttu-id="ad03a-104">作成時刻 (utc) です。</span><span class="sxs-lookup"><span data-stu-id="ad03a-104">Creation time in UTC.</span></span></param>
        <param name="updated"><span data-ttu-id="ad03a-105">最終更新時刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="ad03a-105">Last updated time in UTC.</span></span></param>
        <summary>
            <span data-ttu-id="ad03a-106">IssuerAttributes クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ad03a-106">Initializes a new instance of the IssuerAttributes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerAttributes.Created" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.IssuerAttributes.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.UnixTimeJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="created")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad03a-107">(Utc) には、作成時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="ad03a-107">Gets creation time in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerAttributes.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerAttributes.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad03a-108">取得または設定は、発行者が有効になっているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="ad03a-108">Gets or sets determines whether the issuer is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Updated">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Updated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Updated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerAttributes.Updated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Updated As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Updated : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.IssuerAttributes.Updated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.UnixTimeJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad03a-109">(Utc) には、最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="ad03a-109">Gets last updated time in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>