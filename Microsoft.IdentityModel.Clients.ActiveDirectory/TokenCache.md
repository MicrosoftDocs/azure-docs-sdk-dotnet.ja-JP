<Type Name="TokenCache" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache">
  <TypeSignature Language="C#" Value="public class TokenCache" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi TokenCache extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenCache" />
  <TypeSignature Language="F#" Value="type TokenCache = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="05357-101">トークンのキャッシュ クラスによって使用される<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />アクセスを格納し、トークンを更新します。</span><span class="sxs-lookup"><span data-stu-id="05357-101">Token cache class used by <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" /> to store access and refresh tokens.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenCache ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="05357-102">既定のコンストラクター</span><span class="sxs-lookup"><span data-stu-id="05357-102">Default constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenCache (byte[] state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache : byte[] -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache state" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="state">To be added.</param>
        <summary>
            <span data-ttu-id="05357-103">キャッシュの状態を受け取るコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="05357-103">Constructor receiving state of the cache</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AfterAccess">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification AfterAccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache/TokenCacheNotification AfterAccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" />
      <MemberSignature Language="VB.NET" Value="Public Property AfterAccess As TokenCache.TokenCacheNotification" />
      <MemberSignature Language="F#" Value="member this.AfterAccess : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache+TokenCacheNotification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05357-104">通知方法は、ライブラリのメソッドがキャッシュにアクセス後に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="05357-104">Notification method called after any library method accesses the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeforeAccess">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification BeforeAccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache/TokenCacheNotification BeforeAccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeAccess" />
      <MemberSignature Language="VB.NET" Value="Public Property BeforeAccess As TokenCache.TokenCacheNotification" />
      <MemberSignature Language="F#" Value="member this.BeforeAccess : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeAccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache+TokenCacheNotification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05357-105">メソッドは、任意のライブラリのメソッドの前に呼び出されます。 通知は、キャッシュにアクセスします。</span><span class="sxs-lookup"><span data-stu-id="05357-105">Notification method called before any library method accesses the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeforeWrite">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification BeforeWrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache/TokenCacheNotification BeforeWrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeWrite" />
      <MemberSignature Language="VB.NET" Value="Public Property BeforeWrite As TokenCache.TokenCacheNotification" />
      <MemberSignature Language="F#" Value="member this.BeforeWrite : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.TokenCacheNotification with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.BeforeWrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache+TokenCacheNotification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05357-106">通知メソッドが呼び出されたときに、ライブラリのメソッドは、キャッシュに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="05357-106">Notification method called before any library method writes to the cache.</span></span> <span data-ttu-id="05357-107">この通知は、データベース内の行からキャッシュの状態を再読み込みされ、その行のロックを使用できます。</span><span class="sxs-lookup"><span data-stu-id="05357-107">This notification can be used to reload the cache state from a row in database and lock that row.</span></span> <span data-ttu-id="05357-108">そのデータベースの行のロックを解除する、<see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" />通知します。</span><span class="sxs-lookup"><span data-stu-id="05357-108">That database row can then be unlocked in <see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.AfterAccess" /> notification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public virtual void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="tokenCache.Clear " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="05357-109">すべての項目を削除することによって、キャッシュをクリアします。</span><span class="sxs-lookup"><span data-stu-id="05357-109">Clears the cache by deleting all the items.</span></span> <span data-ttu-id="05357-110">キャッシュが既定の共有キャッシュの場合は、オフにすることは影響ことのすべてのインスタンスに注意してください<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />そのキャッシュを共有します。</span><span class="sxs-lookup"><span data-stu-id="05357-110">Note that if the cache is the default shared cache, clearing it would impact all the instances of <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" /> which share that cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05357-111">キャッシュ内の項目の nunmber を取得します。</span><span class="sxs-lookup"><span data-stu-id="05357-111">Gets the nunmber of items in the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultShared">
      <MemberSignature Language="C#" Value="public static Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache DefaultShared { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache DefaultShared" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.DefaultShared" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultShared As TokenCache" />
      <MemberSignature Language="F#" Value="member this.DefaultShared : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.DefaultShared" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05357-112">静的トークンのキャッシュは明示的に渡さないようにキャッシュ インスタンスの作成中に AuthenticationContext のすべてのインスタンスで共有します。</span><span class="sxs-lookup"><span data-stu-id="05357-112">Static token cache shared by all instances of AuthenticationContext which do not explicitly pass a cache instance during construction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteItem">
      <MemberSignature Language="C#" Value="public virtual void DeleteItem (Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteItem(class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.DeleteItem(Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub DeleteItem (item As TokenCacheItem)" />
      <MemberSignature Language="F#" Value="abstract member DeleteItem : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem -&gt; unit&#xA;override this.DeleteItem : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem -&gt; unit" Usage="tokenCache.DeleteItem item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="05357-113">キャッシュから削除する項目</span><span class="sxs-lookup"><span data-stu-id="05357-113">The item to delete from the cache</span></span></param>
        <summary>
            <span data-ttu-id="05357-114">キャッシュから項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="05357-114">Deletes an item from the cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public void Deserialize (byte[] state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Deserialize(unsigned int8[] state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Deserialize(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub Deserialize (state As Byte())" />
      <MemberSignature Language="F#" Value="member this.Deserialize : byte[] -&gt; unit" Usage="tokenCache.Deserialize state" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="05357-115">Blob としてキャッシュの状態</span><span class="sxs-lookup"><span data-stu-id="05357-115">State of the cache as a blob</span></span></param>
        <summary>
            <span data-ttu-id="05357-116">キャッシュの状態を逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="05357-116">Deserializes state of the cache.</span></span> <span data-ttu-id="05357-117">状態は、シリアル化メソッドを呼び出して以前に受信した blob をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="05357-117">The state should be the blob received earlier by calling the method Serialize.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasStateChanged">
      <MemberSignature Language="C#" Value="public bool HasStateChanged { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasStateChanged" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.HasStateChanged" />
      <MemberSignature Language="VB.NET" Value="Public Property HasStateChanged As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasStateChanged : bool with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.HasStateChanged" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05357-118">取得またはキャッシュの状態が変更されたかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="05357-118">Gets or sets the flag indicating whether cache state has changed.</span></span> <span data-ttu-id="05357-119">ADAL のメソッドは、いずれかが変更した後に、このフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="05357-119">ADAL methods set this flag after any change.</span></span> <span data-ttu-id="05357-120">呼び出し元アプリケーションは、キャッシュの状態を永続化と逆シリアル化の後に、フラグをリセットする必要があります。</span><span class="sxs-lookup"><span data-stu-id="05357-120">Caller application should reset the flag after serializing and persisting the state of the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadItems">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt; ReadItems ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt; ReadItems() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.ReadItems" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ReadItems () As IEnumerable(Of TokenCacheItem)" />
      <MemberSignature Language="F#" Value="abstract member ReadItems : unit -&gt; seq&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt;&#xA;override this.ReadItems : unit -&gt; seq&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt;" Usage="tokenCache.ReadItems " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCacheItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="05357-121">キャッシュ内のすべての項目のリストのコピーを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="05357-121">Reads a copy of the list of all items in the cache.</span></span> 
            </summary>
        <returns><span data-ttu-id="05357-122">キャッシュ内のアイテム</span><span class="sxs-lookup"><span data-stu-id="05357-122">The items in the cache</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public byte[] Serialize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] Serialize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.Serialize" />
      <MemberSignature Language="VB.NET" Value="Public Function Serialize () As Byte()" />
      <MemberSignature Language="F#" Value="member this.Serialize : unit -&gt; byte[]" Usage="tokenCache.Serialize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="05357-123">Blob として、キャッシュの現在の状態をシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="05357-123">Serializes current state of the cache as a blob.</span></span> <span data-ttu-id="05357-124">呼び出し元のアプリケーションでは、blob を保持でき、コンス トラクターに戻り、その blob を渡すことによって、または逆シリアル化メソッドを呼び出すことによって、後で、キャッシュの状態を更新することができます。</span><span class="sxs-lookup"><span data-stu-id="05357-124">Caller application can persist the blob and update the state of the cache later by passing that blob back in constructor or by calling method Deserialize.</span></span>
            </summary>
        <returns><span data-ttu-id="05357-125">Blob としてキャッシュの現在の状態</span><span class="sxs-lookup"><span data-stu-id="05357-125">Current state of the cache as a blob</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>