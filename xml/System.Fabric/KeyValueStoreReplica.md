<Type Name="KeyValueStoreReplica" FullName="System.Fabric.KeyValueStoreReplica">
  <TypeSignature Language="C#" Value="public class KeyValueStoreReplica : System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyValueStoreReplica extends System.Object implements class System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyValueStoreReplica&#xA;Implements IStatefulServiceReplica" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica = class&#xA;    interface IStatefulServiceReplica&#xA;    interface IBackupRestoreReplica" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStatefulServiceReplica</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <span data-ttu-id="e7617-101"><para>サービスのライター - 任意の Service Fabric サービスに統合するための準備完了に、レプリケートされたトランザクション関連のデータ記憶域コンポーネントを提供します。</para></span><span class="sxs-lookup"><span data-stu-id="e7617-101"><para>Provides a transactional, replicated, associative data storage component to service writers - ready for integration into any Service Fabric service.</para></span></span>
            <span data-ttu-id="e7617-102">これは、従来の Service Fabric サービスで使用されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-102">This is used by legacy Service Fabric services.</span></span> <span data-ttu-id="e7617-103">すべての新しいサービスを使用する必要があります、<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">信頼性の高いコレクション</see>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-103">All new services should use the <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">Reliable Collections</see>.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica storeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="e7617-104">キー/値のストアの名前。</span><span class="sxs-lookup"><span data-stu-id="e7617-104">The name of the key/value store.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-105">新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名を格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-105">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e7617-106">ストアの名前は、有効なファイル名の文字に従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-106">The store name should conform to valid filename characters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="e7617-107">キー/値のストアの名前。</span><span class="sxs-lookup"><span data-stu-id="e7617-107">The name of the key/value store.</span></span></para>
        </param>
        <param name="localStoreSettings">
          <para><span data-ttu-id="e7617-108">ローカル ストア用のオプションの設定。</span><span class="sxs-lookup"><span data-stu-id="e7617-108">The optional settings for the local store.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-109">新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名とローカル ストアの設定を格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-109">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name and local store settings.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="e7617-110">キー/値のストアの名前。</span><span class="sxs-lookup"><span data-stu-id="e7617-110">The name of the key/value store.</span></span></para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="e7617-111">キー/値のオプションの設定は、レプリケーターを格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-111">The option settings for the key/value store replicator.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-112">新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のストアの名前を持つクラスし、複製物作成会社の設定を保存します。</span><span class="sxs-lookup"><span data-stu-id="e7617-112">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name and store replicator settings.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e7617-113">ストアの名前は、有効なファイル名の文字に従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-113">The store name should conform to valid filename characters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="e7617-114">キー/値のストアの名前。</span><span class="sxs-lookup"><span data-stu-id="e7617-114">The name of the key/value store.</span></span></para>
        </param>
        <param name="localStoreSettings">
          <para><span data-ttu-id="e7617-115">ローカル ストア用のオプションの設定。</span><span class="sxs-lookup"><span data-stu-id="e7617-115">The optional settings for the local store.</span></span></para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="e7617-116">キー/値のオプションの設定は、レプリケーターを格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-116">The option settings for the key/value store replicator.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-117">新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名、ローカル ストアの設定、および複製物作成会社設定を格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-117">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name, local store settings, and replicator settings.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode notificationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode notificationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, notificationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="notificationMode" Type="System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para><span data-ttu-id="e7617-118">キー/値のストアの名前。</span><span class="sxs-lookup"><span data-stu-id="e7617-118">The name of the key/value store.</span></span></para>
        </param>
        <param name="localStoreSettings">
          <para><span data-ttu-id="e7617-119">ローカル ストア用のオプションの設定。</span><span class="sxs-lookup"><span data-stu-id="e7617-119">The optional settings for the local store.</span></span></para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="e7617-120">キー/値のオプションの設定は、レプリケーターを格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-120">The option settings for the key/value store replicator.</span></span></para>
        </param>
        <param name="notificationMode">
          <para><span data-ttu-id="e7617-121">セカンダリ通知モードを有効にする<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />と<see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />このレプリカでのコールバック。</span><span class="sxs-lookup"><span data-stu-id="e7617-121">The secondary notification mode to enable <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> and <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> callbacks on this replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-122">新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名、ローカル ストアの設定、および複製物作成会社設定を格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-122">Initializes a new instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class with the specified key/value store name, local store settings, and replicator settings.</span></span> <span data-ttu-id="e7617-123">セカンダリ レプリカの通知は通知モードを使用して有効にします。</span><span class="sxs-lookup"><span data-stu-id="e7617-123">Secondary replica notifications are enabled via the notification mode.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplicaSettings kvsSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, class System.Fabric.KeyValueStoreReplicaSettings kvsSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplicaSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplicaSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, kvsSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="kvsSettings" Type="System.Fabric.KeyValueStoreReplicaSettings" />
      </Parameters>
      <Docs>
        <param name="storeName"><span data-ttu-id="e7617-124">キー/値のストアの名前。</span><span class="sxs-lookup"><span data-stu-id="e7617-124">The name of the key/value store.</span></span></param>
        <param name="localStoreSettings"><span data-ttu-id="e7617-125">ローカル ストア用のオプションの設定。</span><span class="sxs-lookup"><span data-stu-id="e7617-125">The optional settings for the local store.</span></span></param>
        <param name="replicatorSettings"><span data-ttu-id="e7617-126">キー/値の省略可能な設定には、レプリケーターが格納されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-126">The optional settings for the key/value store replicator.</span></span></param>
        <param name="kvsSettings"><span data-ttu-id="e7617-127">キー/値の省略可能な設定には、レプリカが格納されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-127">The optional settings for the key/value store replica.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-128">指定したキー/値のストア名、ローカル ストアの設定、レプリケーター設定、およびレプリカの設定を使用して、KeyValueStoreReplica クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e7617-128">Initializes a new instance of the KeyValueStoreReplica class with the specified key/value store name, local store settings, replicator settings, and replica settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit&#xA;override this.Abort : unit -&gt; unit" Usage="keyValueStoreReplica.Abort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-129">このインスタンスを中止、<see cref="T:System.Fabric.KeyValueStoreReplica" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="e7617-129">Aborts this instance of the <see cref="T:System.Fabric.KeyValueStoreReplica" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Add(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Add : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Add (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-130">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-130">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-131">キーまたは (文字列) として追加する値のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e7617-131">The key or index of the value to be added (as a string).</span></span> <span data-ttu-id="e7617-132">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-132">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="e7617-133">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-133">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-134">キー/値のストアを指定したキーによってインデックス設定される値を追加します。</span><span class="sxs-lookup"><span data-stu-id="e7617-134">Adds a value indexed by the specified key to the key/value store.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backup">
      <MemberSignature Language="C#" Value="public void Backup (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Backup(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Backup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Backup (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Backup : string -&gt; unit" Usage="keyValueStoreReplica.Backup backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use BackupAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para><span data-ttu-id="e7617-135">バックアップ先ディレクトリの完全パス。</span><span class="sxs-lookup"><span data-stu-id="e7617-135">The full path of the backup destination directory.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-136">推奨されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="e7617-136">DEPRECATED.</span></span> <span data-ttu-id="e7617-137">指定した宛先ディレクトリへのレプリカのローカル ストアの完全バックアップを実行します。</span><span class="sxs-lookup"><span data-stu-id="e7617-137">Performs a full backup of the replica's local store to the specified destination directory.</span></span> </para>
        </summary>
        <remarks>
          <para>
            <span data-ttu-id="e7617-138">このメソッドは、互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="e7617-138">This method is obsolete.</span></span> <span data-ttu-id="e7617-139">代わりに、<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="e7617-139">Use <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> instead.</span></span></para>
          <para>
            <span data-ttu-id="e7617-140">このメソッドを使用して完全バックアップを作成した後は、増分バックアップはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="e7617-140">Incremental backups are not supported after creating a full backup using this method.</span></span> <span data-ttu-id="e7617-141">使用して<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />以降の増分バックアップが作成される場合は、完全バックアップを作成します。</span><span class="sxs-lookup"><span data-stu-id="e7617-141">Use <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> to create a full backup if subsequent incremental backups are to be created.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupDirectory As String, backupOption As StoreBackupOption, postBackupAsyncFunc As Func(Of StoreBackupInfo, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="e7617-142">バックアップが格納されるディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="e7617-142">The directory where the backup is to be stored.</span></span> <span data-ttu-id="e7617-143">場合<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />、このパラメーターである必要があります<b>null</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-143">If <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, then this parameter should be <b>null</b>.</span></span>
            <span data-ttu-id="e7617-144">それ以外の場合、このパラメーターは指定できません<b>null</b>、空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-144">Otherwise, this parameter cannot be <b>null</b>, empty or contain just whitespace.</span></span> <span data-ttu-id="e7617-145">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="e7617-145">UNC paths may also be provided.</span></span>
            <span data-ttu-id="e7617-146">ディレクトリが存在しない場合は作成されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-146">If the directory doesn't exist, it is created.</span></span> <span data-ttu-id="e7617-147">増分バックアップが失敗したかどうかは、存在し、空でない<see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-147">If it exists and isn't empty, then incremental backup fails with <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.</span></span>
            </param>
        <param name="backupOption">
          <para><span data-ttu-id="e7617-148">バックアップのオプションです。</span><span class="sxs-lookup"><span data-stu-id="e7617-148">The options for the backup.</span></span></para>
        </param>
        <param name="postBackupAsyncFunc">
            <span data-ttu-id="e7617-149">投稿では、Service Fabric を使用するシステムに制御を返す前に、バックアップ後のアクティビティを完了するユーザーによって呼び出される非同期のメソッドをバックアップします。</span><span class="sxs-lookup"><span data-stu-id="e7617-149">The post backup asynchronous method that is invoked by Service Fabric to allow the user to complete any post backup activity before returning control to the system.</span></span>
            <span data-ttu-id="e7617-150">場合<b>null</b>が渡されたこれは、増分バックアップは許可されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-150">If <b>null</b> is passed in for this, incremental backups are disallowed.</span></span>
            <span data-ttu-id="e7617-151">バックアップ後のメソッドが false を返す場合は、増分バックアップは許可されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-151">If the post-backup method returns false, then again, incremental backups are disallowed.</span></span>
            </param>
        <summary>
          <para><span data-ttu-id="e7617-152">非同期的にキー/値のストアのバックアップを作成します。</span><span class="sxs-lookup"><span data-stu-id="e7617-152">Asynchronously creates a backup of the key/value store.</span></span></para>
        </summary>
        <returns><span data-ttu-id="e7617-153">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-153">A task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="e7617-154"><b>PostBackupAsyncFunc</b>バックアップ中にエラーがある場合は呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-154">The <b>postBackupAsyncFunc</b> is not invoked if there is an error during backup.</span></span> <span data-ttu-id="e7617-155">また、ときに呼び出されました<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />ここでは 1 つのバックアップ サイクルを完了する、ユーザーから必要な追加の操作が存在しないためです。</span><span class="sxs-lookup"><span data-stu-id="e7617-155">Also, it is not invoked when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> since there is no further action needed from the user in this case to complete a single backup cycle.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="e7617-156"><b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。</span><span class="sxs-lookup"><span data-stu-id="e7617-156"><b>backupDirectory</b> is <b>null</b> when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="e7617-157"><b>backupDirectory</b>が空か、単なる空白文字が含まれていますと<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />または<b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。</span><span class="sxs-lookup"><span data-stu-id="e7617-157"><b>backupDirectory</b> is empty or contains just whitespaces when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> or <b>backupDirectory</b> is not <b>null</b> when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            <span data-ttu-id="e7617-158">ときに<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.Incremental" />バックアップ ディレクトリには既にファイルまたはサブディレクトリが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-158">When <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> and the backup directory already contains files or sub-directories.</span></span>        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            <span data-ttu-id="e7617-159">ときに、以前に開始されたバックアップが現在進行中です。</span><span class="sxs-lookup"><span data-stu-id="e7617-159">When a previously initiated backup is currently in progress.</span></span>
            </exception>
        <example>
            <span data-ttu-id="e7617-160">以下の簡単な実装の例は、 <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }</span><span class="sxs-lookup"><span data-stu-id="e7617-160">Below is an example of a simple implementation of <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
{
return await CopyBackupToAzureBlobStorage(info);
}</span></span>
</code></example>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="e7617-161">バックアップが格納されるディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="e7617-161">The directory where the backup is to be stored.</span></span> <span data-ttu-id="e7617-162">場合<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />、このパラメーターである必要があります<b>null</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-162">If <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, then this parameter should be <b>null</b>.</span></span>
            <span data-ttu-id="e7617-163">それ以外の場合、このパラメーターは指定できません<b>null</b>、空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-163">Otherwise, this parameter cannot be <b>null</b>, empty or contain just whitespace.</span></span> <span data-ttu-id="e7617-164">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="e7617-164">UNC paths may also be provided.</span></span>
            <span data-ttu-id="e7617-165">ディレクトリが存在しない場合は作成されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-165">If the directory doesn't exist, it is created.</span></span> <span data-ttu-id="e7617-166">増分バックアップが失敗したかどうかは、存在し、空でない<see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-166">If it exists and isn't empty, then incremental backup fails with <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.</span></span>
            </param>
        <param name="backupOption">
          <para><span data-ttu-id="e7617-167">バックアップのオプションです。</span><span class="sxs-lookup"><span data-stu-id="e7617-167">The options for the backup.</span></span></para>
        </param>
        <param name="postBackupAsyncFunc">
            <span data-ttu-id="e7617-168">投稿では、Service Fabric を使用するシステムに制御を返す前に、バックアップ後のアクティビティを完了するユーザーによって呼び出される非同期のメソッドをバックアップします。</span><span class="sxs-lookup"><span data-stu-id="e7617-168">The post backup asynchronous method that is invoked by Service Fabric to allow the user to complete any post backup activity before returning control to the system.</span></span>
            <span data-ttu-id="e7617-169">場合<b>null</b>が渡されたこれは、増分バックアップは許可されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-169">If <b>null</b> is passed in for this, incremental backups are disallowed.</span></span>
            <span data-ttu-id="e7617-170">バックアップ後のメソッドが false を返す場合は、増分バックアップは許可されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-170">If the post-backup method returns false, then again, incremental backups are disallowed.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="e7617-171">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="e7617-171">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-172">非同期的にキー/値のストアのバックアップを作成します。</span><span class="sxs-lookup"><span data-stu-id="e7617-172">Asynchronously creates a backup of the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-173">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-173">A task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="e7617-174"><b>PostBackupAsyncFunc</b>バックアップ中にエラーがある場合は呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-174">The <b>postBackupAsyncFunc</b> is not invoked if there is an error during backup.</span></span> <span data-ttu-id="e7617-175">また、ときに呼び出されました<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />ここでは 1 つのバックアップ サイクルを完了する、ユーザーから必要な追加の操作が存在しないためです。</span><span class="sxs-lookup"><span data-stu-id="e7617-175">Also, it is not invoked when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> since there is no further action needed from the user in this case to complete a single backup cycle.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="e7617-176"><b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。</span><span class="sxs-lookup"><span data-stu-id="e7617-176"><b>backupDirectory</b> is <b>null</b> when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="e7617-177"><b>backupDirectory</b>が空か、単なる空白文字が含まれていますと<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />または<b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。</span><span class="sxs-lookup"><span data-stu-id="e7617-177"><b>backupDirectory</b> is empty or contains just whitespaces when <b>backupOption</b> is not <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> or <b>backupDirectory</b> is not <b>null</b> when <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            <span data-ttu-id="e7617-178">ときに<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.Incremental" />バックアップ ディレクトリには既にファイルまたはサブディレクトリが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-178">When <b>backupOption</b> is <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> and the backup directory already contains files or sub-directories.</span></span>        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            <span data-ttu-id="e7617-179">ときに、以前に開始されたバックアップが現在進行中です。</span><span class="sxs-lookup"><span data-stu-id="e7617-179">When a previously initiated backup is currently in progress.</span></span>
            </exception>
        <example>
            <span data-ttu-id="e7617-180">以下の簡単な実装の例は、 <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }</span><span class="sxs-lookup"><span data-stu-id="e7617-180">Below is an example of a simple implementation of <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
{
return await CopyBackupToAzureBlobStorage(info);
}</span></span>
</code></example>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;ChangeRoleAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para><span data-ttu-id="e7617-181">ターゲット レプリカのロール。</span><span class="sxs-lookup"><span data-stu-id="e7617-181">The target replica role.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e7617-182">現在は使用しません。</span><span class="sxs-lookup"><span data-stu-id="e7617-182">Currently unused.</span></span> <span data-ttu-id="e7617-183">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="e7617-183">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-184">レプリカとそのレプリケーターのレプリカのロールを変更します。</span><span class="sxs-lookup"><span data-stu-id="e7617-184">Changes the replica role of the replica and its replicator.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-185">このレプリカのアドレスを結果タスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-185">A task whose result is the address of this replica.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e7617-186">このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。</span><span class="sxs-lookup"><span data-stu-id="e7617-186">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="e7617-187">ここでは、アプリケーションのレプリカをオーバーライドする必要があります<see cref="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />代わりにします。</span><span class="sxs-lookup"><span data-stu-id="e7617-187">In this case, the application replica should override <see cref="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" /> instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;CloseAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="e7617-188">現在は使用しません。</span><span class="sxs-lookup"><span data-stu-id="e7617-188">Currently unused.</span></span> <span data-ttu-id="e7617-189">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="e7617-189">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-190">レプリカおよびレプリカ セットからオフラインになっているに備えて、レプリケーターを閉じます。</span><span class="sxs-lookup"><span data-stu-id="e7617-190">Closes the replica and its replicator in preparation for going offline from a replica set.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-191">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-191">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e7617-192">レプリカが必ずしもから削除されていない永続的に、レプリカ セットと、後で再度開くことができます。</span><span class="sxs-lookup"><span data-stu-id="e7617-192">The replica has not necessarily been removed permanently from the replica set and may be re-opened at a later time.</span></span> <span data-ttu-id="e7617-193">レプリカを閉じるための一般的な原因は、アップグレードまたは負荷分散の準備として正常にシャット ダウンします。</span><span class="sxs-lookup"><span data-stu-id="e7617-193">The most common causes for closing a replica is graceful shutdown in preparation for upgrade or load balancing.</span></span> <span data-ttu-id="e7617-194">このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。</span><span class="sxs-lookup"><span data-stu-id="e7617-194">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="e7617-195">ここでは、アプリケーションのレプリカをオーバーライドする必要があります<see cref="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" />代わりにします。</span><span class="sxs-lookup"><span data-stu-id="e7617-195">In this case, the application replica should override <see cref="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" /> instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Contains(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Contains : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.Contains (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-196">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-196">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-197">キーまたは (文字列として) を検索する値のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e7617-197">The key or index of the value to look up (as a string).</span></span> <span data-ttu-id="e7617-198">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-198">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-199">キー/値のストアに値が含まれているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="e7617-199">Determines whether a value is contained in the key/value store.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="e7617-200"><languageKeyword>true</languageKeyword>キー/値のストア; に値が含まれている場合<languageKeyword>false</languageKeyword>、それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="e7617-200"><languageKeyword>true</languageKeyword> if the value is contained in the key/value store; <languageKeyword>false</languageKeyword>, otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : unit -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-201">一意な作成<see cref="T:System.Fabric.Transaction" />ストア操作をコミットに使用されるインスタンス、またはキー/値のグループをロールバックします。</span><span class="sxs-lookup"><span data-stu-id="e7617-201">Creates a unique <see cref="T:System.Fabric.Transaction" /> instance, which is used to commit or rollback groups of key/value store operations.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-202">A<see cref="T:System.Fabric.Transaction" />トランザクションを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-202">A <see cref="T:System.Fabric.Transaction" /> object representing a transaction.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction (System.Fabric.KeyValueStoreTransactionSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction(class System.Fabric.KeyValueStoreTransactionSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction(System.Fabric.KeyValueStoreTransactionSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction (settings As KeyValueStoreTransactionSettings) As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : System.Fabric.KeyValueStoreTransactionSettings -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.KeyValueStoreTransactionSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="e7617-203">トランザクションの設定。</span><span class="sxs-lookup"><span data-stu-id="e7617-203">The transaction settings.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-204">一意な作成<see cref="T:System.Fabric.Transaction" />ストア操作をコミットに使用されるインスタンス、またはキー/値のグループをロールバックします。</span><span class="sxs-lookup"><span data-stu-id="e7617-204">Creates a unique <see cref="T:System.Fabric.Transaction" /> instance, which is used to commit or rollback groups of key/value store operations.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-205">A<see cref="T:System.Fabric.Transaction" />トランザクションを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-205">A <see cref="T:System.Fabric.Transaction" /> object representing a transaction.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossReported">
      <MemberSignature Language="C#" Value="public event EventHandler DataLossReported;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler DataLossReported" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />
      <MemberSignature Language="VB.NET" Value="Public Event DataLossReported As EventHandler " />
      <MemberSignature Language="F#" Value="member this.DataLossReported : EventHandler " Usage="member this.DataLossReported : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7617-206">データが失われるイベントのハンドラーです。</span><span class="sxs-lookup"><span data-stu-id="e7617-206">Handler for data loss events.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-207">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-207">The transaction instance.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-208">反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItem" />キー/値のストア内の値。</span><span class="sxs-lookup"><span data-stu-id="e7617-208">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItem" /> values in the key/value store.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-209">A<see cref="T:System.Fabric.KeyValueStoreItem" />列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-209">A <see cref="T:System.Fabric.KeyValueStoreItem" /> enumerator.</span></span></para>
        </returns>
        <remarks>
          <para>
            <span data-ttu-id="e7617-210">昇順を辞書式には、キーによって項目が列挙されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-210">The items are enumerated in lexicographically increasing order by key.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-211">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-211">The transaction instance.</span></span></para>
        </param>
        <param name="keyPrefix">
          <para><span data-ttu-id="e7617-212">(文字列) と一致するように、キーまたはインデックスをプレフィックスします。</span><span class="sxs-lookup"><span data-stu-id="e7617-212">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="e7617-213">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-213">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-214">反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItem" />値のキーが指定されたキーのプレフィックスに一致するキー/値の値が格納されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-214">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItem" /> values in the key/value store, where the value keys match the specified key prefix.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-215">A<see cref="T:System.Fabric.KeyValueStoreItem" />列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-215">A <see cref="T:System.Fabric.KeyValueStoreItem" /> enumerator.</span></span></para>
        </returns>
        <remarks>
          <para>
            <span data-ttu-id="e7617-216">呼び出すことと同じ<see cref="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" />で<b>strictPrefix</b> 'éý' <languageKeyword>true</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-216">Equivalent to calling <see cref="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" /> with <b>strictPrefix</b> set to <languageKeyword>true</languageKeyword>.</span></span>
            </para>
          <para>
            <span data-ttu-id="e7617-217">昇順を辞書式には、キーによって項目が列挙されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-217">The items are enumerated in lexicographically increasing order by key.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-218">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-218">The transaction instance.</span></span></param>
        <param name="keyPrefix"><span data-ttu-id="e7617-219">(文字列) と一致するように、キーまたはインデックスをプレフィックスします。</span><span class="sxs-lookup"><span data-stu-id="e7617-219">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="e7617-220">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-220">Limited to 800 characters in length.</span></span></param>
        <param name="strictPrefix"><span data-ttu-id="e7617-221">True の場合に指定された値を付けたキーのみ<b>keyPrefix</b>が返されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-221">When true, only keys prefixed by the value specified for <b>keyPrefix</b> are returned.</span></span> <span data-ttu-id="e7617-222">一致する、または辞書を超える最初のキーに列挙を開始するそれ以外の場合、 <b>keyPrefix</b>いないキーが複数あるまで継続します。</span><span class="sxs-lookup"><span data-stu-id="e7617-222">Otherwise, enumeration starts at the first key matching or lexicographically greater than <b>keyPrefix</b> and continues until there are no more keys.</span></span> <span data-ttu-id="e7617-223">既定値は <b>true</b> です。</span><span class="sxs-lookup"><span data-stu-id="e7617-223">The default is <b>true</b>.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-224">反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItem" />キー/値のストア内の値。</span><span class="sxs-lookup"><span data-stu-id="e7617-224">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItem" /> values in the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-225">A<see cref="T:System.Fabric.KeyValueStoreItem" />列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-225">A <see cref="T:System.Fabric.KeyValueStoreItem" /> enumerator.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="e7617-226">昇順を辞書式には、キーによって項目が列挙されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-226">The items are enumerated in lexicographically increasing order by key.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-227">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-227">The transaction instance.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-228">反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />キー/値のストア内の値。</span><span class="sxs-lookup"><span data-stu-id="e7617-228">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> values in the key/value store.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-229">A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-229">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> enumerator.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-230">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-230">The transaction instance.</span></span></para>
        </param>
        <param name="keyPrefix">
          <para><span data-ttu-id="e7617-231">(文字列) と一致するように、キーまたはインデックスをプレフィックスします。</span><span class="sxs-lookup"><span data-stu-id="e7617-231">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="e7617-232">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-232">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-233">反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />値のキーが指定されたキーのプレフィックスに一致するキー/値の値が格納されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-233">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> values in the key/value store, where the value keys match the specified key prefix.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-234">A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-234">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> enumerator.</span></span></para>
        </returns>
        <remarks>
            <span data-ttu-id="e7617-235">呼び出すことと同じ<see cref="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" />で<b>strictPrefix</b> 'éý' <languageKeyword>true</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-235">Equivalent to calling <see cref="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" /> with <b>strictPrefix</b> set to <languageKeyword>true</languageKeyword>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-236">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-236">The transaction instance.</span></span></param>
        <param name="keyPrefix"><span data-ttu-id="e7617-237">(文字列) と一致するように、キーまたはインデックスをプレフィックスします。</span><span class="sxs-lookup"><span data-stu-id="e7617-237">The key, or index, prefix to match (as a string).</span></span> <span data-ttu-id="e7617-238">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-238">Limited to 800 characters in length.</span></span></param>
        <param name="strictPrefix"><span data-ttu-id="e7617-239">True の場合に指定された値を付けたキーのみ<b>keyPrefix</b>が返されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-239">When true, only keys prefixed by the value specified for <b>keyPrefix</b> are returned.</span></span> <span data-ttu-id="e7617-240">一致する、または辞書を超える最初のキーに列挙を開始するそれ以外の場合、 <b>keyPrefix</b>いないキーが複数あるまで継続します。</span><span class="sxs-lookup"><span data-stu-id="e7617-240">Otherwise, enumeration starts at the first key matching or lexicographically greater than <b>keyPrefix</b> and continues until there are no more keys.</span></span> <span data-ttu-id="e7617-241">既定値は <b>true</b> です。</span><span class="sxs-lookup"><span data-stu-id="e7617-241">The default is <b>true</b>.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-242">反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />キー/値のストア内の値。</span><span class="sxs-lookup"><span data-stu-id="e7617-242">Returns an enumerator that iterates through the <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> values in the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-243">A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-243">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> enumerator.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem Get (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem Get(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Get(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Get : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.Get (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-244">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-244">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-245">キーまたは (文字列) として取得する値のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e7617-245">The key or index of the value to be retrieved (as a string).</span></span> <span data-ttu-id="e7617-246">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-246">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-247">として格納されている値を取得、<see cref="T:System.Fabric.KeyValueStoreItem" />指定されたキーに関連付けられているオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-247">Gets the stored value, as a <see cref="T:System.Fabric.KeyValueStoreItem" /> object, associated with the specified key.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-248">A<see cref="T:System.Fabric.KeyValueStoreItem" />格納されている値を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-248">A <see cref="T:System.Fabric.KeyValueStoreItem" /> object representing the stored value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentEpoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch GetCurrentEpoch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Fabric.Epoch GetCurrentEpoch() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetCurrentEpoch" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentEpoch () As Epoch" />
      <MemberSignature Language="F#" Value="member this.GetCurrentEpoch : unit -&gt; System.Fabric.Epoch" Usage="keyValueStoreReplica.GetCurrentEpoch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-249">キー/値のストアの現在のエポックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7617-249">Gets the current epoch for the key/value store.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-250">キー/値のストアの現在のエポックです。</span><span class="sxs-lookup"><span data-stu-id="e7617-250">The current epoch for the key/value store.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata GetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata GetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.GetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-251">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-251">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-252">キーまたは (文字列) として取得する値のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e7617-252">The key or index of the value to be retrieved (as a string).</span></span> <span data-ttu-id="e7617-253">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-253">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-254">として、メタデータを取得、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />オブジェクト、指定されたキーに関連付けられている値。</span><span class="sxs-lookup"><span data-stu-id="e7617-254">Gets the metadata, as a <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object, for the value associated with the specified key.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-255">A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />指定した値に関連付けられているメタデータを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-255">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object representing the metadata associated with the specified value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValue">
      <MemberSignature Language="C#" Value="public byte[] GetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.GetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-256">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-256">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-257">キーまたは (文字列) として取得する値のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e7617-257">The key or index of the value to be retrieved (as a string).</span></span> <span data-ttu-id="e7617-258">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-258">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-259">指定したキーに関連付けられているバイト配列として格納されている値を取得します。</span><span class="sxs-lookup"><span data-stu-id="e7617-259">Gets the stored value as a byte array, associated with the specified key.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-260">格納されている値を表すバイト配列。</span><span class="sxs-lookup"><span data-stu-id="e7617-260">A byte array representing the stored value.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreSequenceNumberCheck">
      <MemberSignature Language="C#" Value="public const long IgnoreSequenceNumberCheck = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 IgnoreSequenceNumberCheck = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberSignature Language="VB.NET" Value="Public Const IgnoreSequenceNumberCheck As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable IgnoreSequenceNumberCheck : int64" Usage="System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-261">シーケンス番号のチェックが発生していないことを示します。</span><span class="sxs-lookup"><span data-stu-id="e7617-261">Indicates that sequence number checking should not occur.</span></span></para>
        </summary>
        <remarks>
          <para>
             <span data-ttu-id="e7617-262">シーケンス番号のチェックが発生していないことを示すためにチェック シーケンス番号のパラメーターを受け入れる Api で使用できます。<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></span><span class="sxs-lookup"><span data-stu-id="e7617-262">Can be used in APIs accepting a check sequence number parameter to indicate that sequence number checking should not occur: <list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></span></span>
             
             <span data-ttu-id="e7617-263">これは、チェック シーケンス番号のパラメーターがない API のオーバー ロードを呼び出すことと同じです。<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" /></description></item></list></span><span class="sxs-lookup"><span data-stu-id="e7617-263">This is equivalent to calling API overloads that do not have a check sequence number parameter: <list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" /></description></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="e7617-264">レプリカの初期化情報。</span><span class="sxs-lookup"><span data-stu-id="e7617-264">The initialization information for the replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-265">開くのための準備でレプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e7617-265">Initializes the replica in preparation for opening.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e7617-266">このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。</span><span class="sxs-lookup"><span data-stu-id="e7617-266">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="e7617-267">ここでは、アプリケーションのレプリカをオーバーライドする必要があります<see cref="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" />代わりにします。</span><span class="sxs-lookup"><span data-stu-id="e7617-267">In this case, the application replica should override <see cref="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" /> instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueStoreReplicaSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyValueStoreReplicaSettings As KeyValueStoreReplicaSettings" />
      <MemberSignature Language="F#" Value="member this.KeyValueStoreReplicaSettings : System.Fabric.KeyValueStoreReplicaSettings" Usage="System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplicaSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-268">取得または設定のオプションの設定、<see cref="T:System.Fabric.KeyValueStoreReplica" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-268">Gets or sets the option settings for the <see cref="T:System.Fabric.KeyValueStoreReplica" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e7617-269"><see cref="T:System.Fabric.KeyValueStoreReplica" />オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="e7617-269">The <see cref="T:System.Fabric.KeyValueStoreReplica" /> option settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalStoreSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.LocalStoreSettings LocalStoreSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.LocalStoreSettings LocalStoreSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalStoreSettings As LocalStoreSettings" />
      <MemberSignature Language="F#" Value="member this.LocalStoreSettings : System.Fabric.LocalStoreSettings" Usage="System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalStoreSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-270">取得またはローカルのキー/値のストアのオプションの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7617-270">Gets or sets the option settings for the local key/value store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e7617-271">ローカル ストアのオプション設定。</span><span class="sxs-lookup"><span data-stu-id="e7617-271">The local store option settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode NotificationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode NotificationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotificationMode As KeyValueStoreReplica.SecondaryNotificationMode" />
      <MemberSignature Language="F#" Value="member this.NotificationMode : System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" Usage="System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-272">このレプリカの作成中に指定されたセカンダリ通知モードを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7617-272">Gets the secondary notification mode specified during construction of this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e7617-273">現在の通知モード</span><span class="sxs-lookup"><span data-stu-id="e7617-273">The current secondary notification mode</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="keyValueStoreReplica.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-274">このインスタンスをシャット ダウンに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-274">Called to shut down this instance.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;string&gt; OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para><span data-ttu-id="e7617-275">ターゲットのロール。</span><span class="sxs-lookup"><span data-stu-id="e7617-275">The target role.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e7617-276">現在は使用しません。</span><span class="sxs-lookup"><span data-stu-id="e7617-276">Currently unused.</span></span> <span data-ttu-id="e7617-277">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="e7617-277">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-278">このレプリカのロールが変更されることを示します。</span><span class="sxs-lookup"><span data-stu-id="e7617-278">Indicates that this replica is changing roles.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-279">このレプリカの解決可能なアドレスを結果タスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-279">A task whose result is the resolvable address of this replica.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e7617-280">派生している場合、アプリケーションのレプリカはこのメソッドをオーバーライドする必要があります<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。</span><span class="sxs-lookup"><span data-stu-id="e7617-280">The application replica should override this method if deriving from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="e7617-281">アプリケーションのレプリカを返す必要があります、<see cref="T:System.Threading.Tasks.Task" />をこのレプリカのアドレスの結果。</span><span class="sxs-lookup"><span data-stu-id="e7617-281">The application replica should return a <see cref="T:System.Threading.Tasks.Task" /> whose result is the address of this replica.</span></span> <span data-ttu-id="e7617-282">同様に、(変更なし) を使用して取得できる、システムでこのレプリカのアドレスが格納されている<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-282">This replica address is stored by the system as is and can be retrieved (unmodified) using <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />.</span></span> <span data-ttu-id="e7617-283">アプリケーションは、未処理の変更の役割のすべての呼び出しの完了の背後にあるレプリカ セットの再構成がブロックされるため、適切なタイミングでロールの変更を終了する注意する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-283">The application must take care to complete the role change in a timely manner since reconfiguration of the replica set will be blocked behind the completion of all outstanding change role calls.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="e7617-284">A<see cref="T:System.Threading.CancellationToken" />操作を監視しているオブジェクトの取り消し処理のタスクに通知するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="e7617-284">A <see cref="T:System.Threading.CancellationToken" /> object that the operation is monitoring, which can be used to notify the task of cancellation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-285">このサービス レプリカがシャット ダウンを閉じる必要があるときに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-285">Called when this service replica is being shut down and needs to close.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-286">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="e7617-286">The asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCopyComplete">
      <MemberSignature Language="C#" Value="protected virtual void OnCopyComplete (System.Fabric.KeyValueStoreEnumerator enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnCopyComplete(class System.Fabric.KeyValueStoreEnumerator enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnCopyComplete (enumerator As KeyValueStoreEnumerator)" />
      <MemberSignature Language="F#" Value="abstract member OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit&#xA;override this.OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit" Usage="keyValueStoreReplica.OnCopyComplete enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Fabric.KeyValueStoreEnumerator" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para><span data-ttu-id="e7617-287">セカンダリ上のデータの読み取りに使用される列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-287">The enumerator used to read data on the secondary.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-288">プライマリからのビルドが完了したら、レプリケーション操作の適用を開始する準備が整いましたときに、セカンダリ レプリカで、システムによって呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-288">Called by the system on secondary replicas when they have finished building from the primary and are ready to start applying replication operations.</span></span></para>
          <para><span data-ttu-id="e7617-289">このメソッドはのみ呼び出すことのセカンダリ レプリカの場合、 <see cref="T:System.Fabric.KeyValueStoreReplica" /> 、有効なオブジェクトが構築されて<see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="e7617-289">This method will only be called on secondary replicas if the <see cref="T:System.Fabric.KeyValueStoreReplica" /> object was constructed with a valid <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" /> parameter.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e7617-290"><see cref="T:System.Fabric.KeyValueStoreEnumerator" />オブジェクトは、レプリケーション操作が適用される前にこのメソッドのコンテキスト内で、セカンダリ上のデータの読み取りに使用できます。</span><span class="sxs-lookup"><span data-stu-id="e7617-290">The <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> object can be used to read data on the secondary within the context of this method before any replication operations are applied.</span></span> <span data-ttu-id="e7617-291"><see cref="T:System.Fabric.KeyValueStoreEnumerator" />オブジェクトが正しく不要になった後、このメソッドを返し、このメソッドのコンテキストの外部で使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="e7617-291">The <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> object is no longer valid after this method returns and cannot be used outside the context of this method.</span></span> <span data-ttu-id="e7617-292">アプリケーションは、レプリケーション操作が、セカンダリ レプリカでキューに登録されているが、このメソッドが戻るまでに適用されるを取得するには開始されませんので、適切なタイミングでこのコールバックを完了する注意する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-292">The application must take care to complete this callback in a timely manner since replication operations are being queued on the secondary replica and will not start getting applied until this method returns.</span></span> <span data-ttu-id="e7617-293"><see cref="T:System.Fabric.KeyValueStoreEnumerator" />オブジェクトは 1 つの基になるローカル トランザクションによってバックアップされ、スレッド セーフではありません。</span><span class="sxs-lookup"><span data-stu-id="e7617-293">The <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> object is backed by a single underlying local transaction and is not thread-safe.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="keyValueStoreReplica.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="e7617-294">操作の取り消し状態をチェックするために使用するトークンです。</span><span class="sxs-lookup"><span data-stu-id="e7617-294">The token used to check for cancellation of the operation.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-295">レプリカ セットのことを通知で、データの損失が発生した可能性があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-295">Signals that the replica set may have experienced data loss.</span></span> <span data-ttu-id="e7617-296">アプリケーションは、イベントを非同期的に処理またはを使用するには、このメソッドをオーバーライドできますか、<see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />同期的に処理するイベントです。</span><span class="sxs-lookup"><span data-stu-id="e7617-296">The application can either override this method to process the event asynchronously or use the <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> event to process synchronously.</span></span> <span data-ttu-id="e7617-297">両方は、同じイベントを表します。</span><span class="sxs-lookup"><span data-stu-id="e7617-297">Both represent the same event.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-298">復旧中にデータが変更されたレプリカ セットの再同期する必要があることを示すためには true です。</span><span class="sxs-lookup"><span data-stu-id="e7617-298">True to indicate that data was modified during recovery and the replica set needs to be resynchronized.</span></span> <span data-ttu-id="e7617-299">データが変更されていないことを示すためにそれ以外の場合、false になります。</span><span class="sxs-lookup"><span data-stu-id="e7617-299">Otherwise, false to indicate that data has not been modified.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDatalossReported">
      <MemberSignature Language="C#" Value="protected virtual void OnDatalossReported (EventArgs args);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDatalossReported(class System.EventArgs args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDatalossReported(System.EventArgs)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnDatalossReported (args As EventArgs)" />
      <MemberSignature Language="F#" Value="abstract member OnDatalossReported : EventArgs -&gt; unit&#xA;override this.OnDatalossReported : EventArgs -&gt; unit" Usage="keyValueStoreReplica.OnDatalossReported args" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="args" Type="System.EventArgs" />
      </Parameters>
      <Docs>
        <param name="args">
          <para><span data-ttu-id="e7617-300">現在データが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-300">Currently contains no data.</span></span> <span data-ttu-id="e7617-301">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="e7617-301">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-302">レプリカ セットのことを通知で、データの損失が発生した可能性があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-302">Signals that the replica set may have experienced data loss.</span></span> <span data-ttu-id="e7617-303">アプリケーションのこのメソッドをオーバーライドまたはリッスンできます、<see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />イベント。</span><span class="sxs-lookup"><span data-stu-id="e7617-303">The application can either override this method or listen for the <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> Event.</span></span> <span data-ttu-id="e7617-304">同じイベントを表す両方</span><span class="sxs-lookup"><span data-stu-id="e7617-304">Both represent the same event</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnInitialize">
      <MemberSignature Language="C#" Value="protected virtual void OnInitialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnInitialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnInitialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.OnInitialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="e7617-305">として表されるサービスのレプリカの初期化パラメーター、<see cref="T:System.Fabric.StatefulServiceInitializationParameters" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-305">The initialization parameters for the service replica, represented as a <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-306">新しく作成されたサービスのレプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e7617-306">Initializes a newly created service replica.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnOpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para><span data-ttu-id="e7617-307">A<see cref="T:System.Fabric.ReplicaOpenMode" />このレプリカに対して新しいまたは回復であるかどうかを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-307">A <see cref="T:System.Fabric.ReplicaOpenMode" /> object specifying for this replica whether it is new or recovered.</span></span></para>
        </param>
        <param name="partition">
          <para><span data-ttu-id="e7617-308">A<see cref="T:System.Fabric.IStatefulServicePartition" />このレプリカのステートフルなサービス パーティション情報を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-308">A <see cref="T:System.Fabric.IStatefulServicePartition" /> object representing the stateful service partition information for this replica.</span></span> </para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e7617-309">A<see cref="T:System.Threading.CancellationToken" />操作を監視しているオブジェクトの取り消し処理のタスクに通知するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="e7617-309">A <see cref="T:System.Threading.CancellationToken" /> object that the operation is monitoring, which can be used to notify the task of cancellation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-310">開くには追加のアクションを実行できるように、初期化されたサービス レプリカに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-310">Called on an initialized service replica to open it so that additional actions can be taken.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-311">A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-311">A <see cref="T:System.Threading.Tasks.Task" /> object representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReplicationOperation">
      <MemberSignature Language="C#" Value="protected virtual void OnReplicationOperation (System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnReplicationOperation(class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreNotification&gt; enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnReplicationOperation (enumerator As IEnumerator(Of KeyValueStoreNotification))" />
      <MemberSignature Language="F#" Value="abstract member OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit&#xA;override this.OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit" Usage="keyValueStoreReplica.OnReplicationOperation enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt;" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para><span data-ttu-id="e7617-312">このレプリケーション操作のデータの読み取りに使用される列挙子。</span><span class="sxs-lookup"><span data-stu-id="e7617-312">The enumerator used to read the data in this replication operation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-313">入力方向のレプリケーション操作のセカンダリ レプリカで、システムによって呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-313">Called by the system on secondary replicas for incoming replication operations.</span></span> <span data-ttu-id="e7617-314">各<see cref="T:System.Fabric.KeyValueStoreNotification" />オブジェクトには、1 つの分割不可能なレプリケーション操作のすべてのデータが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-314">Each <see cref="T:System.Fabric.KeyValueStoreNotification" /> object contains all the data for a single atomic replication operation.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e7617-315">このメソッドはのみ呼び出すことのセカンダリ レプリカの場合、 <see cref="T:System.Fabric.KeyValueStoreReplica" /> 、有効なオブジェクトが構築されて<see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-315">This method will only be called on secondary replicas if the <see cref="T:System.Fabric.KeyValueStoreReplica" /> object was constructed with a valid <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />.</span></span></para>
          <para><span data-ttu-id="e7617-316">場合、<see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" />モードを指定し、入力方向のレプリケーション操作は、セカンダリ レプリカ上でローカルに適用されず、メソッドが戻るまで、プライマリを確認します。</span><span class="sxs-lookup"><span data-stu-id="e7617-316">If the <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" /> mode was specified, then the incoming replication operation is not applied locally on the secondary replica and acknowledged to the primary until the method returns.</span></span> <span data-ttu-id="e7617-317">これは、アプリケーションがレプリケーション ストリームをブロックしないようにして、適切なタイミングでこのメソッドから返される注意する必要があることを意味します。</span><span class="sxs-lookup"><span data-stu-id="e7617-317">This implies that the application must take care to return from this method in a timely manner to avoiding blocking the replication stream.</span></span> <span data-ttu-id="e7617-318">想定できないため、このメソッドが戻るまで、受信確認がプライマリに送信されないこと、計測されたレプリケーション操作は既に (または、後であることが保証) によって適用レプリカ セットのレプリカのクォーラムです。</span><span class="sxs-lookup"><span data-stu-id="e7617-318">Since the acknowledgment is not sent to the primary until this method returns, it cannot be assumed that the observed replication operation has already been (or is guaranteed to be in the future) applied by a quorum of replicas in the replica set.</span></span></para>
          <para><span data-ttu-id="e7617-319">場合、<see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" />モードが指定されている、計測されたレプリケーション操作をレプリカ セットのレプリカのクォーラムが既に適用されていることが保証されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-319">If the <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" /> mode was specified, then the observed replication operation is guaranteed to have already been applied by a quorum of replicas in the replica set.</span></span> <span data-ttu-id="e7617-320">さらに、計測されたレプリケーション操作可能性がありますが既にこのセカンダリでローカルに適用され、システムによって、メソッドが呼び出される時点で、プライマリに受信確認します。</span><span class="sxs-lookup"><span data-stu-id="e7617-320">Furthermore, the observed replication operation may have already been applied locally by this secondary and acknowledged to the primary at the time the method is invoked by the system.</span></span> <span data-ttu-id="e7617-321">メソッドのコールバックではこのモードでは、レプリケーション ストリームはブロックされませんが、レプリケーション操作の通知ストリームもブロックされます。</span><span class="sxs-lookup"><span data-stu-id="e7617-321">The method callback will not block the replication stream in this mode, but it will still block the replication operation notification stream.</span></span> <span data-ttu-id="e7617-322">つまり、のみあります未処理 OnReplicationOperation メソッド コールバックは 1 つ特定の時点。</span><span class="sxs-lookup"><span data-stu-id="e7617-322">That is, there will only be one outstanding OnReplicationOperation method callback at any given time.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="e7617-323">操作の取り消し状態をチェックするために使用するトークンです。</span><span class="sxs-lookup"><span data-stu-id="e7617-323">The token used to check for cancellation of the operation.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-324">レプリカの状態が、システムによって正常に復元されていることを通知します。</span><span class="sxs-lookup"><span data-stu-id="e7617-324">Signals that the replica's state was successfully restored by the system.</span></span>
            <span data-ttu-id="e7617-325">これは、システムが内部的にバックアップを復元サービスを経由して復元がトリガーされたときにのみ呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-325">This is invoked only when system internally triggers a restore via the Backup Restore service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;&#xA;override this.OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="keyValueStoreReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;OpenAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para><span data-ttu-id="e7617-326">このレプリカが開かれるコンテキストを指定します。</span><span class="sxs-lookup"><span data-stu-id="e7617-326">Specifies the context under which this replica is being opened.</span></span></para>
        </param>
        <param name="partition">
          <para><span data-ttu-id="e7617-327">このレプリカが属しているセットのレプリカを説明する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-327">Contains information describing the replica set to which this replica belongs.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e7617-328">現在は使用しません。</span><span class="sxs-lookup"><span data-stu-id="e7617-328">Currently unused.</span></span> <span data-ttu-id="e7617-329">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="e7617-329">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-330">オンライン レプリカ セット内の前に、レプリカとそのレプリケーターを開きます。</span><span class="sxs-lookup"><span data-stu-id="e7617-330">Opens the replica and its replicator in preparation for coming online in a replica set.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e7617-331">Open の完了を示すためにタスク<see cref="T:System.Threading.Tasks.Task`1" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-331">A Task to indicate completion of the open <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e7617-332">このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。</span><span class="sxs-lookup"><span data-stu-id="e7617-332">This method does not need to be called explicitly if the application replica derives from <see cref="T:System.Fabric.KeyValueStoreReplica" />, which is the recommended pattern.</span></span> <span data-ttu-id="e7617-333">この場合、アプリケーションのレプリカでは、OnOpenAsync を代わりにオーバーライドする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-333">In this case, the application replica should override OnOpenAsync instead.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-334">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-334">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-335">キーまたはインデックス、(文字列) として削除する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-335">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="e7617-336">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-336">Limited to 800 characters in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-337">指定したキーによってインデックス設定される値を削除します。</span><span class="sxs-lookup"><span data-stu-id="e7617-337">Removes the value indexed by the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string * int64 -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-338">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-338">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-339">キーまたはインデックス、(文字列) として削除する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-339">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="e7617-340">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-340">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="checkSequenceNumber">
          <para><span data-ttu-id="e7617-341">削除するキーの予期されたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="e7617-341">The expected sequence number of the key to be removed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-342">指定したキーによってインデックス設定される値を削除します。</span><span class="sxs-lookup"><span data-stu-id="e7617-342">Removes the value indexed by the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicatorSettings ReplicatorSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ReplicatorSettings ReplicatorSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorSettings As ReplicatorSettings" />
      <MemberSignature Language="F#" Value="member this.ReplicatorSettings : System.Fabric.ReplicatorSettings" Usage="System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-343">取得またはキー/値のストア レプリケーターのオプションの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7617-343">Gets or sets the option settings for the key/value store replicator.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e7617-344">ストアのレプリケーター オプションの設定。</span><span class="sxs-lookup"><span data-stu-id="e7617-344">The store replicator option settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public void Restore (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Restore(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Restore(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restore (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Restore : string -&gt; unit" Usage="keyValueStoreReplica.Restore backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RestoreAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para><span data-ttu-id="e7617-345">バックアップを含むディレクトリの完全パスです。</span><span class="sxs-lookup"><span data-stu-id="e7617-345">The full path to a directory containing a backup.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-346">このレプリカのローカル ストア データベースを呼び出して作成されたバックアップから復元<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-346">Restores this replica's local store database from a backup that was previously created by calling <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e7617-347">これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-347">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="e7617-348">再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-348">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="e7617-349">推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</span><span class="sxs-lookup"><span data-stu-id="e7617-349">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="e7617-350">復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</span><span class="sxs-lookup"><span data-stu-id="e7617-350">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupDirectory As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="e7617-351">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="e7617-351">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="e7617-352">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-352">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="e7617-353">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="e7617-353">UNC paths may also be provided.</span></span>
            </param>
        <summary>
          <para><span data-ttu-id="e7617-354">このレプリカのローカル ストア データベースを呼び出して作成されたバックアップから復元<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-354">Restores this replica's local store database from a backup that was previously created by calling <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span></para>
        </summary>
        <returns><span data-ttu-id="e7617-355">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-355">A task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="e7617-356">内のファイルからストアを復元するときに、更新されたデータが失われるので、復元は進行中に、キー/値のストアへの任意の書き込み操作を実行しないようにお勧め<b>backupDirectory</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-356">It is recommended to not perform any write operations to the key/value store while restore is underway since the updated data would be lost when the store is restored from the files in <b>backupDirectory</b>.</span></span> </para>
          <para><span data-ttu-id="e7617-357">これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-357">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="e7617-358">再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-358">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="e7617-359">推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</span><span class="sxs-lookup"><span data-stu-id="e7617-359">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="e7617-360">復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</span><span class="sxs-lookup"><span data-stu-id="e7617-360">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="e7617-361"><b>backupDirectory</b>は<b>null</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-361"><b>backupDirectory</b> is <b>null</b>.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="e7617-362"><b>backupDirectory</b>が空か、単なる空白文字が含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-362"><b>backupDirectory</b> is empty or contains just whitespaces.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <span data-ttu-id="e7617-363"><b>backupDirectory</b>存在しません。</span><span class="sxs-lookup"><span data-stu-id="e7617-363"><b>backupDirectory</b> does not exist.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="e7617-364">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="e7617-364">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="e7617-365">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-365">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="e7617-366">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="e7617-366">UNC paths may also be provided.</span></span>
            </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e7617-367">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="e7617-367">The cancellation token</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-368">このレプリカのローカル ストア データベースを呼び出して作成されたバックアップから復元<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="e7617-368">Restores this replica's local store database from a backup that was previously created by calling <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span></para>
        </summary>
        <returns><span data-ttu-id="e7617-369">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-369">A task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="e7617-370">内のファイルからストアを復元するときに、更新されたデータが失われるので、復元は進行中に、キー/値のストアへの任意の書き込み操作を実行しないようにお勧め<b>backupDirectory</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-370">It is recommended to not perform any write operations to the key/value store while restore is underway since the updated data would be lost when the store is restored from the files in <b>backupDirectory</b>.</span></span> </para>
          <para><span data-ttu-id="e7617-371">これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-371">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="e7617-372">再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-372">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="e7617-373">推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</span><span class="sxs-lookup"><span data-stu-id="e7617-373">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="e7617-374">復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</span><span class="sxs-lookup"><span data-stu-id="e7617-374">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="e7617-375"><b>backupDirectory</b>は<b>null</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-375"><b>backupDirectory</b> is <b>null</b>.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="e7617-376"><b>backupDirectory</b>が空か、単なる空白文字が含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-376"><b>backupDirectory</b> is empty or contains just whitespaces.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <span data-ttu-id="e7617-377"><b>backupDirectory</b>存在しません。</span><span class="sxs-lookup"><span data-stu-id="e7617-377"><b>backupDirectory</b> does not exist.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Fabric.RestoreSettings settings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, class System.Fabric.RestoreSettings settings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Fabric.RestoreSettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Fabric.RestoreSettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, settings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="settings" Type="System.Fabric.RestoreSettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            <span data-ttu-id="e7617-378">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="e7617-378">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="e7617-379">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-379">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="e7617-380">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="e7617-380">UNC paths may also be provided.</span></span>
            </param>
        <param name="settings">
            <span data-ttu-id="e7617-381">変更する設定は、動作を復元します。</span><span class="sxs-lookup"><span data-stu-id="e7617-381">Settings to modify restore behavior.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="e7617-382">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="e7617-382">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-383">キー/値のストアのレプリカを非同期的に復元します。</span><span class="sxs-lookup"><span data-stu-id="e7617-383">Asynchronously restores the key/value store replica.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-384">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e7617-384">A task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="e7617-385">内のファイルからストアを復元するときに、更新されたデータが失われるので、復元は進行中に、キー/値のストアへの任意の書き込み操作を実行しないようにお勧め<b>backupDirectory</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-385">It is recommended to not perform any write operations to the key/value store while restore is underway since the updated data would be lost when the store is restored from the files in <b>backupDirectory</b>.</span></span> </para>
          <para><span data-ttu-id="e7617-386">これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。</span><span class="sxs-lookup"><span data-stu-id="e7617-386">This is only a local replica restore and the replica set is not automatically restored.</span></span> <span data-ttu-id="e7617-387">再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-387">The entire replica set must be restored by taking additional steps to cause a natural build of other replicas via reconfiguration.</span></span> <span data-ttu-id="e7617-388">推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</span><span class="sxs-lookup"><span data-stu-id="e7617-388">The recommended approach is to restore to an empty service with only a single replica and increase the target replica set size afterwards with a call to <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> if needed.</span></span></para>
          <para><span data-ttu-id="e7617-389">復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</span><span class="sxs-lookup"><span data-stu-id="e7617-389">If the restore is successful, then the replica will restart itself and start using the restored local data after coming back online given that the recommendation to restore to a replica set containing only a single replica was followed.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="e7617-390"><b>backupDirectory</b>は<b>null</b>です。</span><span class="sxs-lookup"><span data-stu-id="e7617-390"><b>backupDirectory</b> is <b>null</b>.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="e7617-391"><b>backupDirectory</b>が空か、単なる空白文字が含まれています。</span><span class="sxs-lookup"><span data-stu-id="e7617-391"><b>backupDirectory</b> is empty or contains just whitespaces.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <span data-ttu-id="e7617-392"><b>backupDirectory</b>存在しません。</span><span class="sxs-lookup"><span data-stu-id="e7617-392"><b>backupDirectory</b> does not exist.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string" Usage="System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e7617-393">取得またはキー/値のストアの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7617-393">Gets or sets the name of the key/value store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e7617-394">キー/値のストアの名前。</span><span class="sxs-lookup"><span data-stu-id="e7617-394">The name of the key/value store.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="e7617-395">ストアの名前は、有効なファイル名の文字に従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="e7617-395">The store name should conform to valid filename characters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryAdd(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryAdd : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryAdd (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-396">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-396">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-397">キーまたはインデックス、(文字列) として追加する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-397">The key, or index, of the value to be added (as a string).</span></span> <span data-ttu-id="e7617-398">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-398">Limited to 800 characters in length.</span></span></param>
        <param name="value"><span data-ttu-id="e7617-399">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-399">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-400">キーと値を指定したキーによってインデックス設定される値を追加する操作を格納します。</span><span class="sxs-lookup"><span data-stu-id="e7617-400">Attempts to add a value indexed by the specified key to the key/value store.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-401">指定したキーが見つかり、追加されていない場合は true。</span><span class="sxs-lookup"><span data-stu-id="e7617-401">True if the specified key was not already found and added.</span></span> <span data-ttu-id="e7617-402">指定したキーが既に存在する場合は false です。</span><span class="sxs-lookup"><span data-stu-id="e7617-402">False if the specified key already exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem TryGet (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem TryGet(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGet(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGet : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.TryGet (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-403">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-403">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-404">キーまたはインデックス、(文字列) として取得する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-404">The key, or index, of the value to be retrieved (as a string).</span></span> <span data-ttu-id="e7617-405">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-405">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-406">として格納されている値を取得しようとしています、<see cref="T:System.Fabric.KeyValueStoreItem" />指定されたキーに関連付けられているオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-406">Attempts to get the stored value, as a <see cref="T:System.Fabric.KeyValueStoreItem" /> object, associated with the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-407">A<see cref="T:System.Fabric.KeyValueStoreItem" />格納されている値を表すオブジェクト、または指定したキーが存在しない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="e7617-407">A <see cref="T:System.Fabric.KeyValueStoreItem" /> object representing the stored value or null if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata TryGetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata TryGetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.TryGetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-408">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-408">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-409">キーまたはインデックス、(文字列) として取得する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-409">The key, or index, of the value to be retrieved (as a string).</span></span> <span data-ttu-id="e7617-410">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-410">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-411">としてのメタデータの取得を試みます、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />オブジェクト、指定されたキーに関連付けられている値。</span><span class="sxs-lookup"><span data-stu-id="e7617-411">Attempts to get the metadata as a <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object, for the value associated with the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-412">A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />オブジェクトのメタデータを表す、指定された値に関連付けられているか、指定したキーが存在しない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="e7617-412">A <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> object representing the metadata associated with the specified value or null if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public byte[] TryGetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] TryGetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.TryGetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-413">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-413">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-414">キーまたはインデックス、(文字列) として取得する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-414">The key, or index, of the value to be retrieved (as a string).</span></span> <span data-ttu-id="e7617-415">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-415">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-416">指定したキーに関連付けられているバイト配列として格納されている値を取得しようとします。</span><span class="sxs-lookup"><span data-stu-id="e7617-416">Attempts to get the stored value as a byte array, associated with the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-417">指定したキーが存在しない場合に、格納されている値または null を表すバイト配列。</span><span class="sxs-lookup"><span data-stu-id="e7617-417">A byte array representing the stored value or null if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-418">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-418">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-419">キーまたはインデックス、(文字列) として削除する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-419">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="e7617-420">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-420">Limited to 800 characters in length.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-421">指定したキーによってインデックス設定される値を削除しようとしています。</span><span class="sxs-lookup"><span data-stu-id="e7617-421">Attempts to remove the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-422">指定したキーが見つかり削除された場合は true。</span><span class="sxs-lookup"><span data-stu-id="e7617-422">True if the specified key was found and removed.</span></span> <span data-ttu-id="e7617-423">指定したキーが存在しない場合は false。</span><span class="sxs-lookup"><span data-stu-id="e7617-423">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string * int64 -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-424">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-424">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-425">キーまたはインデックス、(文字列) として削除する値。</span><span class="sxs-lookup"><span data-stu-id="e7617-425">The key, or index, of the value to be removed (as a string).</span></span> <span data-ttu-id="e7617-426">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-426">Limited to 800 characters in length.</span></span></param>
        <param name="checkSequenceNumber"><span data-ttu-id="e7617-427">削除するキーの予期されたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="e7617-427">The expected sequence number of the key to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-428">指定したキーによってインデックス設定される値を削除しようとしています。</span><span class="sxs-lookup"><span data-stu-id="e7617-428">Attempts to remove the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-429">指定したキーが見つかり削除された場合は true。</span><span class="sxs-lookup"><span data-stu-id="e7617-429">True if the specified key was found and removed.</span></span> <span data-ttu-id="e7617-430">指定したキーが存在しない場合は false。</span><span class="sxs-lookup"><span data-stu-id="e7617-430">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-431">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-431">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-432">キー、または (文字列) として更新する値のインデックス番号します。</span><span class="sxs-lookup"><span data-stu-id="e7617-432">The key, or index, of the value to be updated (as a string).</span></span> <span data-ttu-id="e7617-433">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-433">Limited to 800 characters in length.</span></span></param>
        <param name="value"><span data-ttu-id="e7617-434">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-434">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-435">指定したキーによってインデックス設定される値を更新しようとしています。</span><span class="sxs-lookup"><span data-stu-id="e7617-435">Attempts to update the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-436">指定したキーが見つかり、更新された場合は true。</span><span class="sxs-lookup"><span data-stu-id="e7617-436">True if the specified key was found and updated.</span></span> <span data-ttu-id="e7617-437">指定したキーが存在しない場合は false。</span><span class="sxs-lookup"><span data-stu-id="e7617-437">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase"><span data-ttu-id="e7617-438">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-438">The transaction instance.</span></span></param>
        <param name="key"><span data-ttu-id="e7617-439">キー、または (文字列) として更新する値のインデックス番号します。</span><span class="sxs-lookup"><span data-stu-id="e7617-439">The key, or index, of the value to be updated (as a string).</span></span> <span data-ttu-id="e7617-440">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-440">Limited to 800 characters in length.</span></span></param>
        <param name="value"><span data-ttu-id="e7617-441">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-441">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></param>
        <param name="checkSequenceNumber"><span data-ttu-id="e7617-442">更新するキーの予期されたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="e7617-442">The expected sequence number of the key to be updated.</span></span></param>
        <summary>
            <span data-ttu-id="e7617-443">指定したキーによってインデックス設定される値を更新しようとしています。</span><span class="sxs-lookup"><span data-stu-id="e7617-443">Attempts to update the value indexed by the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="e7617-444">指定したキーが見つかり、更新された場合は true。</span><span class="sxs-lookup"><span data-stu-id="e7617-444">True if the specified key was found and updated.</span></span> <span data-ttu-id="e7617-445">指定したキーが存在しない場合は false。</span><span class="sxs-lookup"><span data-stu-id="e7617-445">False if the specified key does not exist.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-446">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-446">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-447">キーまたは (文字列) として更新する値のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e7617-447">The key or index of the value to be updated (as a string).</span></span> <span data-ttu-id="e7617-448">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-448">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="e7617-449">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-449">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-450">指定したキーに関連付けられている格納されている値を更新します。</span><span class="sxs-lookup"><span data-stu-id="e7617-450">Updates the stored value associated with the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para><span data-ttu-id="e7617-451">トランザクションのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7617-451">The transaction instance.</span></span></para>
        </param>
        <param name="key">
          <para><span data-ttu-id="e7617-452">キーまたは (文字列) として更新する値のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e7617-452">The key or index of the value to be updated (as a string).</span></span> <span data-ttu-id="e7617-453">800 文字の長さに制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-453">Limited to 800 characters in length.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="e7617-454">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-454">The value (as a byte array) to be stored, limited to 2GB in length.</span></span></para>
        </param>
        <param name="checkSequenceNumber">
          <para><span data-ttu-id="e7617-455">更新するキーの予期されたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="e7617-455">The expected sequence number of the key to be updated.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-456">指定したキーによってインデックス設定される値を更新します。</span><span class="sxs-lookup"><span data-stu-id="e7617-456">Updates the value indexed by the specified key.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReplicatorSettings">
      <MemberSignature Language="C#" Value="public void UpdateReplicatorSettings (System.Fabric.ReplicatorSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateReplicatorSettings(class System.Fabric.ReplicatorSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.UpdateReplicatorSettings(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateReplicatorSettings (settings As ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateReplicatorSettings : System.Fabric.ReplicatorSettings -&gt; unit" Usage="keyValueStoreReplica.UpdateReplicatorSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="e7617-457">使用して、キー/値の更新設定には、レプリケーターが格納されます。</span><span class="sxs-lookup"><span data-stu-id="e7617-457">The settings used to update the key/value store replicator.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e7617-458">指定した設定でキーと値のストアのレプリケーターを更新<see cref="T:System.Fabric.ReplicatorSettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e7617-458">Updates the key/value store replicator with the settings in the specified <see cref="T:System.Fabric.ReplicatorSettings" /> object.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>