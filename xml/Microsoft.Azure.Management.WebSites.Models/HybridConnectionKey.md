<Type Name="HybridConnectionKey" FullName="Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey">
  <TypeSignature Language="C#" Value="public class HybridConnectionKey : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionKey extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionKey&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type HybridConnectionKey = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fcbe5-101">ハイブリッド接続のキー コントラクトです。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-101">Hybrid Connection key contract.</span></span> <span data-ttu-id="fcbe5-102">これにハイブリッド接続の送信のキー名と値です。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-102">This has the send key name and value for a Hybrid Connection.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fcbe5-103">HybridConnectionKey クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-103">Initializes a new instance of the HybridConnectionKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionKey (string id = null, string name = null, string kind = null, string type = null, string sendKeyName = null, string sendKeyValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string sendKeyName, string sendKeyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional sendKeyName As String = null, Optional sendKeyValue As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey" Usage="new Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey (id, name, kind, type, sendKeyName, sendKeyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="sendKeyName" Type="System.String" />
        <Parameter Name="sendKeyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="fcbe5-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="fcbe5-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="fcbe5-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="fcbe5-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-107">Resource type.</span></span></param>
        <param name="sendKeyName"><span data-ttu-id="fcbe5-108">キーの送信の名前。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-108">The name of the send key.</span></span></param>
        <param name="sendKeyValue"><span data-ttu-id="fcbe5-109">キーの送信の値。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-109">The value of the send key.</span></span></param>
        <summary>
            <span data-ttu-id="fcbe5-110">HybridConnectionKey クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-110">Initializes a new instance of the HybridConnectionKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendKeyName">
      <MemberSignature Language="C#" Value="public string SendKeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey.SendKeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SendKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SendKeyName : string" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey.SendKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sendKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcbe5-111">キーの送信の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-111">Gets the name of the send key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendKeyValue">
      <MemberSignature Language="C#" Value="public string SendKeyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendKeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey.SendKeyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SendKeyValue As String" />
      <MemberSignature Language="F#" Value="member this.SendKeyValue : string" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey.SendKeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sendKeyValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcbe5-112">キーの送信の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="fcbe5-112">Gets the value of the send key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>