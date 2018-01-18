<Type Name="FileStatusProperties" FullName="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties">
  <TypeSignature Language="C#" Value="public class FileStatusProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileStatusProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class FileStatusProperties" />
  <TypeSignature Language="F#" Value="type FileStatusProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0d587-101">Data Lake Store のファイルまたはディレクトリの情報です。</span><span class="sxs-lookup"><span data-stu-id="0d587-101">Data Lake Store file or directory information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileStatusProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0d587-102">FileStatusProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0d587-102">Initializes a new instance of the FileStatusProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileStatusProperties (Nullable&lt;long&gt; accessTime = null, Nullable&lt;long&gt; blockSize = null, Nullable&lt;long&gt; childrenNum = null, Nullable&lt;long&gt; expirationTime = null, string group = null, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; modificationTime = null, string owner = null, string pathSuffix = null, string permission = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt; type = null, Nullable&lt;bool&gt; aclBit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; accessTime, valuetype System.Nullable`1&lt;int64&gt; blockSize, valuetype System.Nullable`1&lt;int64&gt; childrenNum, valuetype System.Nullable`1&lt;int64&gt; expirationTime, string group, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; modificationTime, string owner, string pathSuffix, string permission, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt; type, valuetype System.Nullable`1&lt;bool&gt; aclBit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.FileType},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accessTime As Nullable(Of Long) = null, Optional blockSize As Nullable(Of Long) = null, Optional childrenNum As Nullable(Of Long) = null, Optional expirationTime As Nullable(Of Long) = null, Optional group As String = null, Optional length As Nullable(Of Long) = null, Optional modificationTime As Nullable(Of Long) = null, Optional owner As String = null, Optional pathSuffix As String = null, Optional permission As String = null, Optional type As Nullable(Of FileType) = null, Optional aclBit As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties (accessTime, blockSize, childrenNum, expirationTime, group, length, modificationTime, owner, pathSuffix, permission, type, aclBit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accessTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="blockSize" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="childrenNum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="modificationTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="pathSuffix" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt;" />
        <Parameter Name="aclBit" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="accessTime"><span data-ttu-id="0d587-103">エポック以降のタイマー刻みとしての最終アクセス時刻です。</span><span class="sxs-lookup"><span data-stu-id="0d587-103">the last access time as ticks since the epoch.</span></span></param>
        <param name="blockSize"><span data-ttu-id="0d587-104">ファイルのブロック サイズ。</span><span class="sxs-lookup"><span data-stu-id="0d587-104">the block size for the file.</span></span></param>
        <param name="childrenNum"><span data-ttu-id="0d587-105">ディレクトリ内の子の数。</span><span class="sxs-lookup"><span data-stu-id="0d587-105">the number of children in the directory.</span></span></param>
        <param name="expirationTime"><span data-ttu-id="0d587-106">存在する場合、エポック以降のティックとして、有効期限を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-106">Gets the expiration time, if any, as ticks since the epoch.</span></span> <span data-ttu-id="0d587-107">値が 0 または DateTime.MaxValue 場合の有効期限はありません。</span><span class="sxs-lookup"><span data-stu-id="0d587-107">If the value is 0 or DateTime.MaxValue there is no expiration.</span></span></param>
        <param name="group"><span data-ttu-id="0d587-108">グループの所有者。</span><span class="sxs-lookup"><span data-stu-id="0d587-108">the group owner.</span></span></param>
        <param name="length"><span data-ttu-id="0d587-109">ファイル内のバイト数。</span><span class="sxs-lookup"><span data-stu-id="0d587-109">the number of bytes in a file.</span></span></param>
        <param name="modificationTime"><span data-ttu-id="0d587-110">タイマー刻みとしてエポック以降の更新時刻。</span><span class="sxs-lookup"><span data-stu-id="0d587-110">the modification time as ticks since the epoch.</span></span></param>
        <param name="owner"><span data-ttu-id="0d587-111">所有者であるユーザー。</span><span class="sxs-lookup"><span data-stu-id="0d587-111">the user who is the owner.</span></span></param>
        <param name="pathSuffix"><span data-ttu-id="0d587-112">パスのサフィックス。</span><span class="sxs-lookup"><span data-stu-id="0d587-112">the path suffix.</span></span></param>
        <param name="permission"><span data-ttu-id="0d587-113">アクセス許可を文字列として表されます。</span><span class="sxs-lookup"><span data-stu-id="0d587-113">the permission represented as an string.</span></span></param>
        <param name="type"><span data-ttu-id="0d587-114">パス オブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="0d587-114">the type of the path object.</span></span> <span data-ttu-id="0d587-115">使用可能な値が含まれます 'FILE'、'DIRECTORY'。</span><span class="sxs-lookup"><span data-stu-id="0d587-115">Possible values include: 'FILE', 'DIRECTORY'</span></span></param>
        <param name="aclBit"><span data-ttu-id="0d587-116">拡張 acl が有効になっているかどうかを示すフラグします。</span><span class="sxs-lookup"><span data-stu-id="0d587-116">flag to indicate if extended acls are enabled</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d587-117">FileStatusProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0d587-117">Initializes a new instance of the FileStatusProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AccessTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AccessTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.AccessTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTime As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AccessTime : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.AccessTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accessTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-118">タイマー刻みとして新しいエポック以降の最終アクセス時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-118">Gets the last access time as ticks since the epoch.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AclBit">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AclBit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AclBit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.AclBit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AclBit As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AclBit : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.AclBit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aclBit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-119">拡張 acl が有効になっているかどうかを示すためにフラグを取得</span><span class="sxs-lookup"><span data-stu-id="0d587-119">Gets flag to indicate if extended acls are enabled</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; BlockSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; BlockSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.BlockSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlockSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.BlockSize : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.BlockSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blockSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-120">ファイルのブロック サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-120">Gets the block size for the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChildrenNum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ChildrenNum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ChildrenNum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.ChildrenNum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ChildrenNum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ChildrenNum : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.ChildrenNum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="childrenNum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-121">ディレクトリ内の子の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-121">Gets the number of children in the directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="msExpirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-122">存在する場合、エポック以降のティックとして、有効期限を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-122">Gets the expiration time, if any, as ticks since the epoch.</span></span> <span data-ttu-id="0d587-123">値が 0 または DateTime.MaxValue 場合の有効期限はありません。</span><span class="sxs-lookup"><span data-stu-id="0d587-123">If the value is 0 or DateTime.MaxValue there is no expiration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Group">
      <MemberSignature Language="C#" Value="public string Group { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Group" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Group" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Group As String" />
      <MemberSignature Language="F#" Value="member this.Group : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Group" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="group")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-124">グループの所有者を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-124">Gets the group owner.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Length : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-125">ファイル内のバイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-125">Gets the number of bytes in a file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModificationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ModificationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ModificationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.ModificationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ModificationTime As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ModificationTime : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.ModificationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="modificationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-126">タイマー刻みとして新しいエポック以降の変更時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-126">Gets the modification time as ticks since the epoch.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Owner" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Owner" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="owner")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-127">所有者であるユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-127">Gets the user who is the owner.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathSuffix">
      <MemberSignature Language="C#" Value="public string PathSuffix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.PathSuffix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PathSuffix As String" />
      <MemberSignature Language="F#" Value="member this.PathSuffix : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.PathSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-128">パスのサフィックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-128">Gets the path suffix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permission">
      <MemberSignature Language="C#" Value="public string Permission { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Permission" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Permission" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Permission As String" />
      <MemberSignature Language="F#" Value="member this.Permission : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Permission" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permission")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-129">文字列として表される、アクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-129">Gets the permission represented as an string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt; Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As Nullable(Of FileType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.FileStatusProperties.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FileType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d587-130">パス オブジェクトの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d587-130">Gets the type of the path object.</span></span> <span data-ttu-id="0d587-131">使用可能な値が含まれます 'FILE'、'DIRECTORY'。</span><span class="sxs-lookup"><span data-stu-id="0d587-131">Possible values include: 'FILE', 'DIRECTORY'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>