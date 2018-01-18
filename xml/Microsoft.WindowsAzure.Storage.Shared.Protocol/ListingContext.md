<Type Name="ListingContext" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext">
  <TypeSignature Language="C#" Value="public class ListingContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ListingContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
  <TypeSignature Language="VB.NET" Value="Public Class ListingContext" />
  <TypeSignature Language="F#" Value="type ListingContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a1c84-101">列挙操作の一覧のコンテキストを表します。</span><span class="sxs-lookup"><span data-stu-id="a1c84-101">Represents the listing context for enumeration operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListingContext (string prefix, Nullable&lt;int&gt; maxResults);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (prefix As String, maxResults As Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext : string * Nullable&lt;int&gt; -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" Usage="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext (prefix, maxResults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="a1c84-102">リソース名のプレフィックス。</span><span class="sxs-lookup"><span data-stu-id="a1c84-102">The resource name prefix.</span></span></param>
        <param name="maxResults"><span data-ttu-id="a1c84-103">5000 の操作あたりの上限に達するまでの 1 つの操作で返されるリソースの最大数。</span><span class="sxs-lookup"><span data-stu-id="a1c84-103">The maximum number of resources to return in a single operation, up to the per-operation limit of 5000.</span></span></param>
        <summary>
            <span data-ttu-id="a1c84-104"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a1c84-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext.Marker" />
      <MemberSignature Language="VB.NET" Value="Public Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext.Marker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1c84-105">取得またはマーカー値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1c84-105">Gets or sets the Marker value.</span></span>
            </summary>
        <value><span data-ttu-id="a1c84-106">マーカー値です。</span><span class="sxs-lookup"><span data-stu-id="a1c84-106">The Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1c84-107">取得または MaxResults 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1c84-107">Gets or sets the MaxResults value.</span></span>
            </summary>
        <value><span data-ttu-id="a1c84-108">MaxResults の値です。</span><span class="sxs-lookup"><span data-stu-id="a1c84-108">The MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1c84-109">取得またはプレフィックス値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1c84-109">Gets or sets the Prefix value.</span></span>
            </summary>
        <value><span data-ttu-id="a1c84-110">プレフィックスの値です。</span><span class="sxs-lookup"><span data-stu-id="a1c84-110">The Prefix value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>