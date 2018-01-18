<Type Name="JsonWebKeyVerifier" FullName="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier">
  <TypeSignature Language="C#" Value="public abstract class JsonWebKeyVerifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JsonWebKeyVerifier extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JsonWebKeyVerifier" />
  <TypeSignature Language="F#" Value="type JsonWebKeyVerifier = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="76aa3-101">クラスのインスタンスを検証する<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />キーの種類に従ってします。</span><span class="sxs-lookup"><span data-stu-id="76aa3-101">A class that verifies instances of <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> according to key type.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected JsonWebKeyVerifier (string kty);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string kty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kty As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier : string -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier kty" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kty"><span data-ttu-id="76aa3-102">この検証が適用するキーの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-102">Indicates which type of key this verifier applies to.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-103">指定された値の設定の新しいインスタンスを初期化、<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-103">Initializes a new instance setting the specified value in the <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> property.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="76aa3-104">指定した値が場合<code>null</code>、空または空白文字。</span><span class="sxs-lookup"><span data-stu-id="76aa3-104">If the specified value is <code>null</code>, empty or whitespace.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="76aa3-105">場合は、指定された値には、無効な文字が含まれています。</span><span class="sxs-lookup"><span data-stu-id="76aa3-105">If the specified value contains invalid characters.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddCompatibleOperations">
      <MemberSignature Language="C#" Value="protected abstract void AddCompatibleOperations (System.Collections.Generic.ICollection&lt;string&gt; compatibleOperations);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AddCompatibleOperations(class System.Collections.Generic.ICollection`1&lt;string&gt; compatibleOperations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddCompatibleOperations(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AddCompatibleOperations (compatibleOperations As ICollection(Of String))" />
      <MemberSignature Language="F#" Value="abstract member AddCompatibleOperations : System.Collections.Generic.ICollection&lt;string&gt; -&gt; unit" Usage="jsonWebKeyVerifier.AddCompatibleOperations compatibleOperations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="compatibleOperations" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="compatibleOperations">To be added.</param>
        <summary>
            <span data-ttu-id="76aa3-106">型を持つがこのオブジェクトによって処理されるキーを持つ実行可能なすべての操作を指定されたコレクションに追加します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-106">Adds to the specified collection all operations that can be performed with keys whose type is handled by this object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyOperation.Sign" />
        <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyOperation.Verify" />
      </Docs>
    </Member>
    <Member MemberName="AddItem&lt;T&gt;">
      <MemberSignature Language="C#" Value="protected static void AddItem&lt;T&gt; (ref System.Collections.Generic.ICollection&lt;T&gt; items, T newItem);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig void AddItem&lt;T&gt;(class System.Collections.Generic.ICollection`1&lt;!!T&gt;&amp; items, !!T newItem) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddItem``1(System.Collections.Generic.ICollection{``0}@,``0)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Sub AddItem(Of T) (ByRef items As ICollection(Of T), newItem As T)" />
      <MemberSignature Language="F#" Value="static member AddItem :  * 'T -&gt; unit" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddItem (items, newItem)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.ICollection&lt;T&gt;&amp;" RefType="ref" />
        <Parameter Name="newItem" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="items">To be added.</param>
        <param name="newItem">To be added.</param>
        <summary>
            <span data-ttu-id="76aa3-107">コレクションを作成する (必要な場合) の操作を結合するヘルパー メソッドを項目を追加するとします。</span><span class="sxs-lookup"><span data-stu-id="76aa3-107">Helper method that joins the operation of creating a collection (if required) and adding an item to it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <see cref="T:System.Collections.Generic.List`1" />
      </Docs>
    </Member>
    <Member MemberName="AddUsedProperties">
      <MemberSignature Language="C#" Value="protected abstract void AddUsedProperties (System.Collections.Generic.ICollection&lt;string&gt; usedProperties);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AddUsedProperties(class System.Collections.Generic.ICollection`1&lt;string&gt; usedProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddUsedProperties(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AddUsedProperties (usedProperties As ICollection(Of String))" />
      <MemberSignature Language="F#" Value="abstract member AddUsedProperties : System.Collections.Generic.ICollection&lt;string&gt; -&gt; unit" Usage="jsonWebKeyVerifier.AddUsedProperties usedProperties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usedProperties" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="usedProperties">To be added.</param>
        <summary>
            <span data-ttu-id="76aa3-108">キーの型はこのオブジェクトによって処理に使用されるすべての JsonWebKey プロパティを指定されたコレクションに追加します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-108">Adds to the specified collection all JsonWebKey properties that are useful to keys whose type is handled by this object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-109">このメソッドが JSON プロパティ名をなど、追加する必要があります<code>"crv"</code>、 <code>"p"</code>, などです。C# のプロパティ名は追加しないでください。</span><span class="sxs-lookup"><span data-stu-id="76aa3-109">This method must add JSON property names, such as <code>"crv"</code>, <code>"p"</code>, etc. It must not add C# property names.</span></span></para>
        <para><span data-ttu-id="76aa3-110">このメソッドを追加する必要はありません<code>"kid"</code>、<code>"kty"</code>と<code>"key_ops"</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-110">This method doesn't have to add <code>"kid"</code>, <code>"kty"</code> and <code>"key_ops"</code>.</span></span>
            <span data-ttu-id="76aa3-111">アプリケーションのプロパティは、すべてのキーに有用であると見なされます。</span><span class="sxs-lookup"><span data-stu-id="76aa3-111">Thes properties are assumed to be useful to all keys.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="GetVerifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier GetVerifier (string kty);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier GetVerifier(string kty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetVerifier (kty As String) As JsonWebKeyVerifier" />
      <MemberSignature Language="F#" Value="static member GetVerifier : string -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier kty" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kty">To be added.</param>
        <summary>
            <span data-ttu-id="76aa3-112">Kty 値が登録されていない場合は、null、または、指定した kty 値の登録された、検証機能を返します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-112">Returns the verifier registered for the specified kty value, or null if the kty value was not registered.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      </Docs>
    </Member>
    <Member MemberName="HasSecretKey">
      <MemberSignature Language="C#" Value="public abstract bool HasSecretKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasSecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.HasSecretKey" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property HasSecretKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasSecretKey : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.HasSecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76aa3-113">このオブジェクトによって検証キーの種類にハードウェア キー トークンなど、シークレットのコンポーネントが含まれているかどうかに指示します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-113">Tells if the type of key verified by this object contains a secret component, such as a hardware key token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="76aa3-114">true</span><span class="sxs-lookup"><span data-stu-id="76aa3-114">true</span></span></code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsAnyPrivateKeyParamSpecified">
      <MemberSignature Language="C#" Value="public virtual bool IsAnyPrivateKeyParamSpecified (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; specifiedProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsAnyPrivateKeyParamSpecified(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; specifiedProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsAnyPrivateKeyParamSpecified(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsAnyPrivateKeyParamSpecified (webKey As JsonWebKey, ByRef specifiedProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsAnyPrivateKeyParamSpecified : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsAnyPrivateKeyParamSpecified : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsAnyPrivateKeyParamSpecified (webKey, specifiedProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="specifiedProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-115">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-115">The instance to verify.</span></span></param>
        <param name="specifiedProps"><span data-ttu-id="76aa3-116">指定したプロパティの一覧を示す変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-116">A reference to a variable that tells the list of specified properties.</span></span> <span data-ttu-id="76aa3-117">呼び出し元が変数に設定する必要があります<code>null</code>し、このメソッドが戻る場合にのみ、値を調べて<code>true</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-117">Callers must set the variable to <code>null</code> and examine the value only if this method returns <code>true</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-118">かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、秘密キーを表す 1 つまたは複数のプロパティの値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="76aa3-118">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values in one or more properties that represent the private key.</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="76aa3-119"><code>true</code>秘密キーを記述するには、少なくとも 1 つのプロパティに値が見つかった場合<code>false</code>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="76aa3-119"><code>true</code> if a value is found in at least one property that describe the private key; <code>false</code> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-120">このメソッドは、偶発的な漏えいから秘密キー マテリアルを保護するのに使用されます。</span><span class="sxs-lookup"><span data-stu-id="76aa3-120">This method is used to protect private key material from accidental leakage.</span></span></para>
        <para><span data-ttu-id="76aa3-121">秘密キー プロパティ (キーの種類) を指定しないかどうか、インスタンスで、メソッドが返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="76aa3-121">If no private key property (for the key type) is specified in the instance, the method must return</span></span>
            <span data-ttu-id="76aa3-122"><code>false</code>変更しないと、<paramref name="specifiedProps" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76aa3-122"><code>false</code> and not modify the <paramref name="specifiedProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="76aa3-123">1 つまたは複数の秘密キーのプロパティが指定されているかどうか、メソッドが返す必要があります<code>true</code>し、必要に応じて設定<paramref name="specifiedProps" />値を持つ - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -指定したプロパティを含むです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-123">If one or more private key property is specified, the method must return <code>true</code> and optionally set <paramref name="specifiedProps" /> with a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing the specified properties.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="IsOperationCompatible">
      <MemberSignature Language="C#" Value="public bool IsOperationCompatible (string opName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsOperationCompatible(string opName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationCompatible(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsOperationCompatible (opName As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOperationCompatible : string -&gt; bool" Usage="jsonWebKeyVerifier.IsOperationCompatible opName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="opName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="opName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOperationValid">
      <MemberSignature Language="C#" Value="public static bool IsOperationValid (string opName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsOperationValid(string opName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationValid(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsOperationValid (opName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsOperationValid : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationValid opName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="opName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="opName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsPrivateKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPrivateKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPrivateKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPrivateKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPrivateKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPrivateKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">To be added.</param>
        <param name="missingProps">To be added.</param>
        <summary>
            <span data-ttu-id="76aa3-124">同じ<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />、ですが、秘密キーです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-124">Same as <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />, but for the private key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsPrivateKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPrivateKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPrivateKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPrivateKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPrivateKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPrivateKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">To be added.</param>
        <param name="errorMsg">To be added.</param>
        <summary>
            <span data-ttu-id="76aa3-125">同じ<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />、ですが、秘密キーです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-125">Same as <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />, but for the private key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPropertyUsed">
      <MemberSignature Language="C#" Value="public bool IsPropertyUsed (string propName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsPropertyUsed(string propName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPropertyUsed(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsPropertyUsed (propName As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPropertyUsed : string -&gt; bool" Usage="jsonWebKeyVerifier.IsPropertyUsed propName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsPublicKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPublicKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPublicKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPublicKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPublicKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPublicKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-126">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-126">The instance to verify.</span></span></param>
        <param name="missingProps"><span data-ttu-id="76aa3-127">不足しているプロパティの一覧を示す変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-127">A reference to a variable that tells the list of missing properties.</span></span> <span data-ttu-id="76aa3-128">呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-128">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-129">かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、公開キーを表すプロパティに値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="76aa3-129">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values at properties that represent the public key.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-130">かどうかは、インスタンスで必要な公開キーのすべてのプロパティ (キーの種類) が指定された、メソッドが返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="76aa3-130">If all required public key properties (for the key type) are specified in the instance, the method must return</span></span>
            <span data-ttu-id="76aa3-131"><code>true</code>変更しないと、<paramref name="missingProps" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76aa3-131"><code>true</code> and not modify the <paramref name="missingProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="76aa3-132">一部のパブリック キー プロパティがないメソッドが返す必要があります<code>false</code>設定と<paramref name="missingProps" />値を持つ - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -欠損しているすべてのプロパティを含むです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-132">If some public key property is missing, the method must return <code>false</code> and set <paramref name="missingProps" /> with a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing all missing properties.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyCrypto">
      <MemberSignature Language="C#" Value="public abstract bool IsPublicKeyCrypto { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPublicKeyCrypto" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyCrypto" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property IsPublicKeyCrypto As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPublicKeyCrypto : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyCrypto" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76aa3-133">このオブジェクトによって検証キーの型が公開キー アルゴリズムをサポートしているかどうかに指示します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-133">Tells if the type of key verified by this object supports public key algorithms.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="76aa3-134">true</span><span class="sxs-lookup"><span data-stu-id="76aa3-134">true</span></span></code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsPublicKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPublicKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPublicKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPublicKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPublicKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPublicKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-135">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-135">The instance to verify.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="76aa3-136">エラー メッセージを格納する変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-136">A reference to a variable that will contain an error message.</span></span> <span data-ttu-id="76aa3-137">呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-137">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-138">かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、可能性のある有効な公開キーが含まれています (「解説」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="76aa3-138">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains a possibly valid public key (see remarks).</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-139">キーを完全に検証すると、リソースの量の unfeasable がかかる場合があります、ために、このメソッドは明らかな問題を確認するだけあります。</span><span class="sxs-lookup"><span data-stu-id="76aa3-139">Because fully validating a key may require unfeasable amount of resources, this method only has to check for obvious issues.</span></span> <span data-ttu-id="76aa3-140">指針としては、定数時間で実行する場合、コードがその明らかな問題をのみ検証すると言います。</span><span class="sxs-lookup"><span data-stu-id="76aa3-140">As a guideline, we say that the code only verifies obvious issues if it runs in constant time.</span></span>
            <span data-ttu-id="76aa3-141">何もしない実装で完全に有効と戻り値だけである<code>true</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-141">It's perfectly valid for implementors to do nothing and simply return <code>true</code>.</span></span></para>
        <para><span data-ttu-id="76aa3-142">このメソッドが想定する<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />が呼び出され、返される<code>true</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-142">This method assumes that <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> was called and returned <code>true</code>.</span></span> <span data-ttu-id="76aa3-143">これは、必要なプロパティが存在する、もう一度テストしません。</span><span class="sxs-lookup"><span data-stu-id="76aa3-143">It doesn't test again for the presence of required properties.</span></span> <span data-ttu-id="76aa3-144">スローする可能性が<see cref="T:System.NullReferenceException" />場合は、呼び出し元が認識されない<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />返す<code>true</code>最初。</span><span class="sxs-lookup"><span data-stu-id="76aa3-144">It may throw <see cref="T:System.NullReferenceException" /> if the caller doesn't see <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> returning <code>true</code> first.</span></span></para>
        <para><span data-ttu-id="76aa3-145">このメソッドを返す必要があるかどうか valiation コードが検出されない問題、<code>true</code>の値を変更することがなく<paramref name="errorMsg" />です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-145">If the valiation code finds no issue, this method must return <code>true</code> without modifying the value of <paramref name="errorMsg" />.</span></span></para>
        <para><span data-ttu-id="76aa3-146">いくつかの問題が見つからないかどうかは、このメソッドが返す必要があります<code>false</code>で詳細を確認し、<paramref name="errorMsg" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76aa3-146">If some issue is found, this method must return <code>false</code> and tell more details in the <paramref name="errorMsg" /> parameter.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="IsSecretKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsSecretKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSecretKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSecretKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecretKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSecretKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSecretKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-147">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-147">The instance to verify.</span></span></param>
        <param name="missingProps"><span data-ttu-id="76aa3-148">不足しているプロパティの一覧を示す変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-148">A reference to a variable that tells the list of missing properties.</span></span> <span data-ttu-id="76aa3-149">呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-149">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-150">かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、秘密キーを表すプロパティに値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="76aa3-150">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values at properties that represent the secret key.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-151">かどうかは、インスタンスで必要な秘密キーのすべてのプロパティ (キーの種類) が指定された、メソッドが返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="76aa3-151">If all required secret key properties (for the key type) are specified in the instance, the method must return</span></span>
            <span data-ttu-id="76aa3-152"><code>true</code>変更しないと、<paramref name="missingProps" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76aa3-152"><code>true</code> and not modify the <paramref name="missingProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="76aa3-153">一部のプロパティがないメソッドが返す必要があります<code>false</code>設定と<paramref name="missingProps" />値 - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -欠損しているすべてのプロパティを含むです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-153">If some property is missing, the method must return <code>false</code> and set <paramref name="missingProps" /> to a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing all missing properties.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="IsSecretKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsSecretKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSecretKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSecretKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecretKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSecretKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSecretKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-154">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-154">The instance to verify.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="76aa3-155">エラー メッセージを格納する変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-155">A reference to a variable that will contain an error message.</span></span> <span data-ttu-id="76aa3-156">呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-156">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-157">かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、可能性のある有効な秘密キーが含まれています (「解説」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="76aa3-157">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains a possibly valid secret key (see remarks).</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-158">キーを完全に検証すると、リソースの量の unfeasable がかかる場合があります、ために、このメソッドは明らかな問題を確認するだけあります。</span><span class="sxs-lookup"><span data-stu-id="76aa3-158">Because fully validating a key may require unfeasable amount of resources, this method only has to check for obvious issues.</span></span> <span data-ttu-id="76aa3-159">指針としては、定数時間で実行する場合、コードがその明らかな問題をのみ検証すると言います。</span><span class="sxs-lookup"><span data-stu-id="76aa3-159">As a guideline, we say that the code only verifies obvious issues if it runs in constant time.</span></span>
            <span data-ttu-id="76aa3-160">何もしない実装で完全に有効と戻り値だけである<code>true</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-160">It's perfectly valid for implementors to do nothing and simply return <code>true</code>.</span></span></para>
        <para><span data-ttu-id="76aa3-161">このメソッドが想定する<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />が呼び出され、返される<code>true</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-161">This method assumes that <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> was called and returned <code>true</code>.</span></span> <span data-ttu-id="76aa3-162">これは、必要なプロパティが存在する、もう一度テストしません。</span><span class="sxs-lookup"><span data-stu-id="76aa3-162">It doesn't test again for the presence of required properties.</span></span> <span data-ttu-id="76aa3-163">スローする可能性が<see cref="T:System.NullReferenceException" />場合は、呼び出し元が認識されない<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />返す<code>true</code>最初。</span><span class="sxs-lookup"><span data-stu-id="76aa3-163">It may throw <see cref="T:System.NullReferenceException" /> if the caller doesn't see <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> returning <code>true</code> first.</span></span></para>
        <para><span data-ttu-id="76aa3-164">このメソッドを返す必要があるかどうか valiation コードが検出されない問題、<code>true</code>の値を変更することがなく<paramref name="errorMsg" />です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-164">If the valiation code finds no issue, this method must return <code>true</code> without modifying the value of <paramref name="errorMsg" />.</span></span></para>
        <para><span data-ttu-id="76aa3-165">いくつかの問題が見つからないかどうかは、このメソッドが返す必要があります<code>false</code>で詳細を確認し、<paramref name="errorMsg" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76aa3-165">If some issue is found, this method must return <code>false</code> and tell more details in the <paramref name="errorMsg" /> parameter.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsSymmetricKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSymmetricKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSymmetricKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSymmetricKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSymmetricKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSymmetricKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-166">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-166">The instance to verify.</span></span></param>
        <param name="missingProps"><span data-ttu-id="76aa3-167">不足しているプロパティの一覧を示す変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-167">A reference to a variable that tells the list of missing properties.</span></span> <span data-ttu-id="76aa3-168">呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-168">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-169">かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、対称キーを表すプロパティに値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="76aa3-169">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains values at properties that represent the symmetric key.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-170">かどうかは、インスタンスで必要な対称キーのすべてのプロパティ (キーの種類) が指定された、メソッドが返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="76aa3-170">If all required symmetric key properties (for the key type) are specified in the instance, the method must return</span></span>
            <span data-ttu-id="76aa3-171"><code>true</code>変更しないと、<paramref name="missingProps" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76aa3-171"><code>true</code> and not modify the <paramref name="missingProps" /> parameter.</span></span></para>
        <para><span data-ttu-id="76aa3-172">一部のプロパティがないメソッドが返す必要があります<code>false</code>設定と<paramref name="missingProps" />値 - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -欠損しているすべてのプロパティを含むです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-172">If some property is missing, the method must return <code>false</code> and set <paramref name="missingProps" /> to a value - typically a <see cref="T:System.Collections.Generic.List`1" /> - containing all missing properties.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyCrypto">
      <MemberSignature Language="C#" Value="public abstract bool IsSymmetricKeyCrypto { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSymmetricKeyCrypto" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyCrypto" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property IsSymmetricKeyCrypto As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSymmetricKeyCrypto : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyCrypto" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76aa3-173">このオブジェクトによって検証キーの種類が対称キーのアルゴリズムをサポートしているかどうかに指示します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-173">Tells if the type of key verified by this object supports symmetric key algorithms.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="76aa3-174">true</span><span class="sxs-lookup"><span data-stu-id="76aa3-174">true</span></span></code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsSymmetricKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSymmetricKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSymmetricKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSymmetricKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSymmetricKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSymmetricKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-175">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-175">The instance to verify.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="76aa3-176">エラー メッセージを格納する変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-176">A reference to a variable that will contain an error message.</span></span> <span data-ttu-id="76aa3-177">呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-177">Callers must set the variable to <code>null</code>, and examine the value only if this method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-178">かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、可能性のある有効な対称キーが含まれています (「解説」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="76aa3-178">Determines if the specified <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" /> instance contains a possibly valid symmetric key (see remarks).</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-179">キーを完全に検証すると、リソースの量の unfeasable がかかる場合があります、ために、このメソッドは明らかな問題を確認するだけあります。</span><span class="sxs-lookup"><span data-stu-id="76aa3-179">Because fully validating a key may require unfeasable amount of resources, this method only has to check for obvious issues.</span></span> <span data-ttu-id="76aa3-180">指針としては、定数時間で実行する場合、コードがその明らかな問題をのみ検証すると言います。</span><span class="sxs-lookup"><span data-stu-id="76aa3-180">As a guideline, we say that the code only verifies obvious issues if it runs in constant time.</span></span>
            <span data-ttu-id="76aa3-181">何もしない実装で完全に有効と戻り値だけである<code>true</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-181">It's perfectly valid for implementors to do nothing and simply return <code>true</code>.</span></span></para>
        <para><span data-ttu-id="76aa3-182">このメソッドが想定する<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />が呼び出され、返される<code>true</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-182">This method assumes that <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> was called and returned <code>true</code>.</span></span> <span data-ttu-id="76aa3-183">これは、必要なプロパティが存在する、もう一度テストしません。</span><span class="sxs-lookup"><span data-stu-id="76aa3-183">It doesn't test again for the presence of required properties.</span></span> <span data-ttu-id="76aa3-184">スローする可能性が<see cref="T:System.NullReferenceException" />場合は、呼び出し元が認識されない<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />返す<code>true</code>最初。</span><span class="sxs-lookup"><span data-stu-id="76aa3-184">It may throw <see cref="T:System.NullReferenceException" /> if the caller doesn't see <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" /> returning <code>true</code> first.</span></span></para>
        <para><span data-ttu-id="76aa3-185">このメソッドを返す必要があるかどうか valiation コードが検出されない問題、<code>true</code>の値を変更することがなく<paramref name="errorMsg" />です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-185">If the valiation code finds no issue, this method must return <code>true</code> without modifying the value of <paramref name="errorMsg" />.</span></span></para>
        <para><span data-ttu-id="76aa3-186">いくつかの問題が見つからないかどうかは、このメソッドが返す必要があります<code>false</code>で詳細を確認し、<paramref name="errorMsg" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76aa3-186">If some issue is found, this method must return <code>false</code> and tell more details in the <paramref name="errorMsg" /> parameter.</span></span></para>
      </Docs>
    </Member>
    <Member MemberName="Kty">
      <MemberSignature Language="C#" Value="public string Kty { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kty As String" />
      <MemberSignature Language="F#" Value="member this.Kty : string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76aa3-187">この検証が適用するキーの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-187">Indicates which type of key this verifier applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static void Register (Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier verifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Register(class Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier verifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Register (verifier As JsonWebKeyVerifier)" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier -&gt; unit" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register verifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="verifier" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" />
      </Parameters>
      <Docs>
        <param name="verifier"><span data-ttu-id="76aa3-188">登録を検証します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-188">The verifier to register.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-189">登録の検証機能、<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />値。</span><span class="sxs-lookup"><span data-stu-id="76aa3-189">Registers a verifier for a <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" /> value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="SurroundWithQuotes">
      <MemberSignature Language="C#" Value="protected static string SurroundWithQuotes (System.Collections.Generic.ICollection&lt;string&gt; items);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig string SurroundWithQuotes(class System.Collections.Generic.ICollection`1&lt;string&gt; items) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.SurroundWithQuotes(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function SurroundWithQuotes (items As ICollection(Of String)) As String" />
      <MemberSignature Language="F#" Value="static member SurroundWithQuotes : System.Collections.Generic.ICollection&lt;string&gt; -&gt; string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.SurroundWithQuotes items" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="items">To be added.</param>
        <summary>
            <span data-ttu-id="76aa3-190">二重引用符を含む文字列値を囲むヘルパー メソッドです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-190">Helper method that surrounds string values with double-quotes.</span></span> 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <code><span data-ttu-id="76aa3-191">"Foo"、「バー」</span><span class="sxs-lookup"><span data-stu-id="76aa3-191">"Foo", "Bar"</span></span></code>
      </Docs>
    </Member>
    <Member MemberName="ValidateKeyParameterSize">
      <MemberSignature Language="C#" Value="protected static bool ValidateKeyParameterSize (byte[] value, string name, int requiredSize, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig bool ValidateKeyParameterSize(unsigned int8[] value, string name, int32 requiredSize, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.ValidateKeyParameterSize(System.Byte[],System.String,System.Int32,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function ValidateKeyParameterSize (value As Byte(), name As String, requiredSize As Integer, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member ValidateKeyParameterSize : byte[] * string * int *  -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.ValidateKeyParameterSize (value, name, requiredSize, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="requiredSize" Type="System.Int32" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="76aa3-192">検証する配列。</span><span class="sxs-lookup"><span data-stu-id="76aa3-192">The array to validate.</span></span></param>
        <param name="name"><span data-ttu-id="76aa3-193">エラー メッセージを構築するために使用できる配列名。</span><span class="sxs-lookup"><span data-stu-id="76aa3-193">The array name, which may be used to build error messages.</span></span></param>
        <param name="requiredSize"><span data-ttu-id="76aa3-194">必要なサイズ (バイト)。</span><span class="sxs-lookup"><span data-stu-id="76aa3-194">The required size, in bytes.</span></span></param>
        <param name="errorMsg"><span data-ttu-id="76aa3-195">エラー メッセージを格納する変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-195">A reference to a variable that will contain the error message.</span></span> <span data-ttu-id="76aa3-196">メソッドが返された場合のみ設定<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-196">This is only set if the method returns <code>false</code>.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-197">バイト配列のサイズを検証するヘルパー メソッドです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-197">Helper method that validates the size of a byte array.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="76aa3-198"><code>true</code>配列は、有効なサイズを場合<code>false otherwise</code>.</span><span class="sxs-lookup"><span data-stu-id="76aa3-198"><code>true</code> if the array has a valid size; <code>false otherwise</code>.</span></span></returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-199">有効な配列には、次の条件を満たしています。</span><span class="sxs-lookup"><span data-stu-id="76aa3-199">A valid array meets the following criteria:</span></span></para>
        <list type="bullet">
          <item>
            <description><span data-ttu-id="76aa3-200"><code>null</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-200">is not <code>null</code>;</span></span></description>
          </item>
          <item>
            <description><span data-ttu-id="76aa3-201">長さが少なくとも<paramref name="requiredSize" />; と</span><span class="sxs-lookup"><span data-stu-id="76aa3-201">the length is at least <paramref name="requiredSize" />; and</span></span></description>
          </item>
          <item>
            <description><span data-ttu-id="76aa3-202">余分な先頭バイトは、すべてがゼロです。</span><span class="sxs-lookup"><span data-stu-id="76aa3-202">excess leading bytes are all zeros.</span></span></description>
          </item>
        </list>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="public bool Verify (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options options, ref string error);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Verify(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options options, string&amp; error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      <MemberSignature Language="F#" Value="member this.Verify : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options *  -&gt; bool" Usage="jsonWebKeyVerifier.Verify (webKey, options, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="options" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options" />
        <Parameter Name="error" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"><span data-ttu-id="76aa3-203">確認するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="76aa3-203">The instance to verify.</span></span></param>
        <param name="options"><span data-ttu-id="76aa3-204">検証の動作方法を示します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-204">Tells how verification is to behave.</span></span></param>
        <param name="error"><span data-ttu-id="76aa3-205">検証に失敗した場合に、エラー メッセージを指示する変数への参照。</span><span class="sxs-lookup"><span data-stu-id="76aa3-205">A reference to a variable that will tell the error message, if verification fails.</span></span> <span data-ttu-id="76aa3-206">メソッドが返された場合のみ設定<code>false</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-206">This is only set if the method returns <code>false</code>.</span></span> <span data-ttu-id="76aa3-207">メソッドを返す場合<code>true</code>、例外がスローまたは、<paramref name="error" />は自分では変更されません。</span><span class="sxs-lookup"><span data-stu-id="76aa3-207">If the method returns <code>true</code> or throws an exception, the <paramref name="error" /> will not me modified.</span></span></param>
        <summary>
            <span data-ttu-id="76aa3-208">指定した JsonWebKey インスタンスを検証します。</span><span class="sxs-lookup"><span data-stu-id="76aa3-208">Verifies the specified JsonWebKey instance.</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="76aa3-209"><code>true</code>JsonWebKey 値は、有効な場合<code>false otherwise</code>です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-209"><code>true</code> if the JsonWebKey value is valid, <code>false otherwise</code>.</span></span></returns>
        <remarks>To be added.</remarks>
        <para><span data-ttu-id="76aa3-210">検証を調べ、<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />検証インスタンスを選択するプロパティ (詳細については、次を参照してください。、<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />メソッド)。</span><span class="sxs-lookup"><span data-stu-id="76aa3-210">Verification first examines the <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" /> property to select a verifier instance (for more information, see the <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" /> method).</span></span> <span data-ttu-id="76aa3-211">見つかった場合は、検証機能は、確認して、キーが、対応するキーの種類に準拠しているかどうかに使用されます。</span><span class="sxs-lookup"><span data-stu-id="76aa3-211">If a verifier is found, it's used to check if the key conforms to the corresponding key type.</span></span></para>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="76aa3-212">場合、<paramref name="webKey" />パラメーターが null です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-212">If the <paramref name="webKey" /> parameter is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="76aa3-213">場合、<paramref name="options" />パラメーターに無効なオプションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="76aa3-213">If the <paramref name="options" /> parameter contains invalid options.</span></span></exception>
        <exception cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerificationException"><span data-ttu-id="76aa3-214">JsonWebKey オブジェクトが無効であり、オプション場合<see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" />が指定されました。</span><span class="sxs-lookup"><span data-stu-id="76aa3-214">If the JsonWebKey object is invalid and the option <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" /> was specified.</span></span></exception>
        <altmember cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options" />
      </Docs>
    </Member>
    <Member MemberName="VerifyByKeyType">
      <MemberSignature Language="C#" Value="public static bool VerifyByKeyType (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options options, ref string error);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool VerifyByKeyType(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options options, string&amp; error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.VerifyByKeyType(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      <MemberSignature Language="F#" Value="static member VerifyByKeyType : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options *  -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.VerifyByKeyType (webKey, options, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="options" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options" />
        <Parameter Name="error" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"></param>
        <param name="options"></param>
        <param name="error"></param>
        <summary>
            <span data-ttu-id="76aa3-215">インスタンスを検証します指定 JsonWebKey に従って<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />です。</span><span class="sxs-lookup"><span data-stu-id="76aa3-215">Verifies the specified JsonWebKey instance according to <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      </Docs>
    </Member>
  </Members>
</Type>