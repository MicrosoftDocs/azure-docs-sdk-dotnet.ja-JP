<Type Name="StorageUri" FullName="Microsoft.WindowsAzure.Storage.StorageUri">
  <TypeSignature Language="C#" Value="public sealed class StorageUri : IEquatable&lt;Microsoft.WindowsAzure.Storage.StorageUri&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageUri extends System.Object implements class System.IEquatable`1&lt;class Microsoft.WindowsAzure.Storage.StorageUri&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.StorageUri" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageUri&#xA;Implements IEquatable(Of StorageUri)" />
  <TypeSignature Language="F#" Value="type StorageUri = class&#xA;    interface IEquatable&lt;StorageUri&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.WindowsAzure.Storage.StorageUri&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6070b-101">Microsoft Azure ストレージ リソースのプライマリとセカンダリの場所の Uri が含まれています。</span><span class="sxs-lookup"><span data-stu-id="6070b-101">Contains the URIs for both the primary and secondary locations of a Microsoft Azure Storage resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageUri (Uri primaryUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri primaryUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (primaryUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageUri : Uri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="new Microsoft.WindowsAzure.Storage.StorageUri primaryUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="primaryUri"><span data-ttu-id="6070b-102"><see cref="T:System.Uri" />プライマリ エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="6070b-102">The <see cref="T:System.Uri" /> for the primary endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="6070b-103">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />クラス、ストレージ アカウントのプライマリ エンドポイントを使用します。</span><span class="sxs-lookup"><span data-stu-id="6070b-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> class using the primary endpoint for the storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageUri (Uri primaryUri, Uri secondaryUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri primaryUri, class System.Uri secondaryUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.#ctor(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (primaryUri As Uri, secondaryUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageUri : Uri * Uri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="new Microsoft.WindowsAzure.Storage.StorageUri (primaryUri, secondaryUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryUri" Type="System.Uri" />
        <Parameter Name="secondaryUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="primaryUri"><span data-ttu-id="6070b-104"><see cref="T:System.Uri" />プライマリ エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="6070b-104">The <see cref="T:System.Uri" /> for the primary endpoint.</span></span></param>
        <param name="secondaryUri"><span data-ttu-id="6070b-105"><see cref="T:System.Uri" />拠点のエンドポイントにします。</span><span class="sxs-lookup"><span data-stu-id="6070b-105">The <see cref="T:System.Uri" /> for the secondary endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="6070b-106">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />クラス、ストレージ アカウントのプライマリとセカンダリ エンドポイントを使用します。</span><span class="sxs-lookup"><span data-stu-id="6070b-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> class using the primary and secondary endpoints for the storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.WindowsAzure.Storage.StorageUri other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.WindowsAzure.Storage.StorageUri other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.Equals(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="storageUri.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="6070b-107">このオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6070b-107">An object to compare with this object.</span></span></param>
        <summary>
            <span data-ttu-id="6070b-108">現在のオブジェクトが、同じ型の別のオブジェクトと等しいかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="6070b-108">Indicates whether the current object is equal to another object of the same type.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="6070b-109"><c>true</c>現在のオブジェクトが等しい場合、<paramref name="other" />パラメーターです。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6070b-109"><c>true</c> if the current object is equal to the <paramref name="other" /> parameter; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="storageUri.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="6070b-110">このインスタンスと比較する <see cref="T:System.Object" />。</span><span class="sxs-lookup"><span data-stu-id="6070b-110">The <see cref="T:System.Object" /> to compare with this instance.</span></span></param>
        <summary>
            <span data-ttu-id="6070b-111">指定した <see cref="T:System.Object" /> がこのインスタンスと等しいかどうかを判定します。</span><span class="sxs-lookup"><span data-stu-id="6070b-111">Determines whether the specified <see cref="T:System.Object" /> is equal to this instance.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="6070b-112"><c>true</c>場合、指定した<see cref="T:System.Object" />、それ以外のこのインスタンスと等しい<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6070b-112"><c>true</c> if the specified <see cref="T:System.Object" /> is equal to this instance; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="storageUri.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6070b-113">このインスタンスのハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="6070b-113">Returns a hash code for this instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6070b-114">このインスタンスのハッシュ コード。ハッシュ アルゴリズムでもハッシュ テーブルのようなデータ構造でも使用できるもの。</span><span class="sxs-lookup"><span data-stu-id="6070b-114">A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.</span></span> 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUri">
      <MemberSignature Language="C#" Value="public Uri GetUri (Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri GetUri(valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.GetUri(Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUri (location As StorageLocation) As Uri" />
      <MemberSignature Language="F#" Value="member this.GetUri : Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Uri" Usage="storageUri.GetUri location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="6070b-115"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="6070b-115">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></param>
        <summary>
            <span data-ttu-id="6070b-116">指定した場所にストレージ アカウントのエンドポイントの URI を返します。</span><span class="sxs-lookup"><span data-stu-id="6070b-116">Returns the URI for the storage account endpoint at the specified location.</span></span>
            </summary>
        <returns><span data-ttu-id="6070b-117"><see cref="T:System.Uri" />のエンドポイントの指定された場所。</span><span class="sxs-lookup"><span data-stu-id="6070b-117">The <see cref="T:System.Uri" /> for the endpoint at the the specified location.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.WindowsAzure.Storage.StorageUri uri1, Microsoft.WindowsAzure.Storage.StorageUri uri2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.WindowsAzure.Storage.StorageUri uri1, class Microsoft.WindowsAzure.Storage.StorageUri uri2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.op_Equality(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (uri1 As StorageUri, uri2 As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="uri1 = uri2" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri1" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="uri2" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="uri1"><span data-ttu-id="6070b-118">比較する最初の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6070b-118">The first <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object to compare.</span></span></param>
        <param name="uri2"><span data-ttu-id="6070b-119">比較する 2 番目の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6070b-119">The second <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object to compare.</span></span></param>
        <summary>
            <span data-ttu-id="6070b-120">比較する 2 つ<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />の等価のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6070b-120">Compares two <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> objects for equivalency.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="6070b-121"><c>true</c>場合、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />オブジェクトと等価の値がある、それ以外の<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6070b-121"><c>true</c> if the <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> objects have equivalent values; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.WindowsAzure.Storage.StorageUri uri1, Microsoft.WindowsAzure.Storage.StorageUri uri2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.WindowsAzure.Storage.StorageUri uri1, class Microsoft.WindowsAzure.Storage.StorageUri uri2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.op_Inequality(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (uri1 As StorageUri, uri2 As StorageUri) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.StorageUri.op_Inequality (uri1, uri2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri1" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="uri2" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="uri1"><span data-ttu-id="6070b-122">比較する最初の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6070b-122">The first <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object to compare.</span></span></param>
        <param name="uri2"><span data-ttu-id="6070b-123">比較する 2 番目の <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6070b-123">The second <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object to compare.</span></span></param>
        <summary>
            <span data-ttu-id="6070b-124">比較する 2 つ<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />不一致のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6070b-124">Compares two <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> objects for non-equivalency.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="6070b-125"><c>true</c>場合、<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />オブジェクトが等価でない値を持つ、それ以外の<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="6070b-125"><c>true</c> if the <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> objects have non-equivalent values; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryUri">
      <MemberSignature Language="C#" Value="public Uri PrimaryUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri PrimaryUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageUri.PrimaryUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryUri As Uri" />
      <MemberSignature Language="F#" Value="member this.PrimaryUri : Uri" Usage="Microsoft.WindowsAzure.Storage.StorageUri.PrimaryUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6070b-126">ストレージ アカウントのプライマリの場所のエンドポイントです。</span><span class="sxs-lookup"><span data-stu-id="6070b-126">The endpoint for the primary location for the storage account.</span></span>
            </summary>
        <value><span data-ttu-id="6070b-127"><see cref="T:System.Uri" />プライマリ エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="6070b-127">The <see cref="T:System.Uri" /> for the primary endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryUri">
      <MemberSignature Language="C#" Value="public Uri SecondaryUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SecondaryUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageUri.SecondaryUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SecondaryUri : Uri" Usage="Microsoft.WindowsAzure.Storage.StorageUri.SecondaryUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6070b-128">ストレージ アカウントの 2 次拠点のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="6070b-128">The endpoint for the secondary location for the storage account.</span></span>
            </summary>
        <value><span data-ttu-id="6070b-129"><see cref="T:System.Uri" />拠点のエンドポイントにします。</span><span class="sxs-lookup"><span data-stu-id="6070b-129">The <see cref="T:System.Uri" /> for the secondary endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageUri.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storageUri.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6070b-130">このインスタンスを表す <see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="6070b-130">Returns a <see cref="T:System.String" /> that represents this instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6070b-131">このインスタンスを表す <see cref="T:System.String" />。</span><span class="sxs-lookup"><span data-stu-id="6070b-131">A <see cref="T:System.String" /> that represents this instance.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>