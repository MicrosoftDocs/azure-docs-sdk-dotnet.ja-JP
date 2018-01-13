<Type Name="DeletedSite" FullName="Microsoft.Azure.Management.WebSites.Models.DeletedSite">
  <TypeSignature Language="C#" Value="public class DeletedSite" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedSite extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.DeletedSite" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedSite" />
  <TypeSignature Language="F#" Value="type DeletedSite = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b842-101">削除されたアプリです。</span><span class="sxs-lookup"><span data-stu-id="1b842-101">A deleted app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSite ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DeletedSite.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b842-102">DeletedSite クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b842-102">Initializes a new instance of the DeletedSite class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSite (Nullable&lt;int&gt; id = null, string deletedTimestamp = null, string subscription = null, string resourceGroup = null, string name = null, string slot = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; id, string deletedTimestamp, string subscription, string resourceGroup, string name, string slot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DeletedSite.#ctor(System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As Nullable(Of Integer) = null, Optional deletedTimestamp As String = null, Optional subscription As String = null, Optional resourceGroup As String = null, Optional name As String = null, Optional slot As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.DeletedSite : Nullable&lt;int&gt; * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.DeletedSite" Usage="new Microsoft.Azure.Management.WebSites.Models.DeletedSite (id, deletedTimestamp, subscription, resourceGroup, name, slot)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="deletedTimestamp" Type="System.String" />
        <Parameter Name="subscription" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="slot" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1b842-103">削除されたサイトの数値 id</span><span class="sxs-lookup"><span data-stu-id="1b842-103">Numeric id for the deleted site</span></span></param>
        <param name="deletedTimestamp"><span data-ttu-id="1b842-104">アプリが削除されたときの UTC 時間です。</span><span class="sxs-lookup"><span data-stu-id="1b842-104">Time in UTC when the app was deleted.</span></span></param>
        <param name="subscription"><span data-ttu-id="1b842-105">削除されたサイトを含むサブスクリプション</span><span class="sxs-lookup"><span data-stu-id="1b842-105">Subscription containing the deleted site</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="1b842-106">削除されたサイトが含まれているリソース グループ</span><span class="sxs-lookup"><span data-stu-id="1b842-106">ResourceGroup that contained the deleted site</span></span></param>
        <param name="name"><span data-ttu-id="1b842-107">削除されたサイトの名前</span><span class="sxs-lookup"><span data-stu-id="1b842-107">Name of the deleted site</span></span></param>
        <param name="slot"><span data-ttu-id="1b842-108">削除されたサイトのスロット</span><span class="sxs-lookup"><span data-stu-id="1b842-108">Slot of the deleted site</span></span></param>
        <summary>
            <span data-ttu-id="1b842-109">DeletedSite クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b842-109">Initializes a new instance of the DeletedSite class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedTimestamp">
      <MemberSignature Language="C#" Value="public string DeletedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeletedTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DeletedSite.DeletedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedTimestamp As String" />
      <MemberSignature Language="F#" Value="member this.DeletedTimestamp : string" Usage="Microsoft.Azure.Management.WebSites.Models.DeletedSite.DeletedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deletedTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b842-110">アプリが削除されたときに、時刻 (utc) を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b842-110">Gets time in UTC when the app was deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DeletedSite.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Id : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DeletedSite.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b842-111">取得または削除されたサイトの数値 id を設定</span><span class="sxs-lookup"><span data-stu-id="1b842-111">Gets or sets numeric id for the deleted site</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DeletedSite.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.WebSites.Models.DeletedSite.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="1b842-112">削除されたサイトの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b842-112">Gets name of the deleted site</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DeletedSite.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.DeletedSite.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b842-113">削除されたサイトが含まれているリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="1b842-113">Gets resourceGroup that contained the deleted site</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Slot">
      <MemberSignature Language="C#" Value="public string Slot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Slot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DeletedSite.Slot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Slot As String" />
      <MemberSignature Language="F#" Value="member this.Slot : string" Usage="Microsoft.Azure.Management.WebSites.Models.DeletedSite.Slot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="slot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b842-114">削除されたサイトのスロットを取得します</span><span class="sxs-lookup"><span data-stu-id="1b842-114">Gets slot of the deleted site</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscription">
      <MemberSignature Language="C#" Value="public string Subscription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subscription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DeletedSite.Subscription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscription As String" />
      <MemberSignature Language="F#" Value="member this.Subscription : string" Usage="Microsoft.Azure.Management.WebSites.Models.DeletedSite.Subscription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b842-115">削除されたサイトを含むサブスクリプションの取得</span><span class="sxs-lookup"><span data-stu-id="1b842-115">Gets subscription containing the deleted site</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>