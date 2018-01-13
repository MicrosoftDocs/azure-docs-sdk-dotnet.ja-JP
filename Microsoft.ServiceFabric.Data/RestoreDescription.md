<Type Name="RestoreDescription" FullName="Microsoft.ServiceFabric.Data.RestoreDescription">
  <TypeSignature Language="C#" Value="public struct RestoreDescription" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreDescription extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreDescription" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreDescription" />
  <TypeSignature Language="F#" Value="type RestoreDescription = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b335d-101">RestoreDescription には、すべてのステートフル サービス レプリカを復元するために必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="b335d-101">A RestoreDescription contains all of the information necessary to restore a stateful service replica.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupFolderPath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription backupFolderPath" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="b335d-102">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b335d-102">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="b335d-103">このパラメーターを null にすることはできません、空または空白のみで構成されます。</span><span class="sxs-lookup"><span data-stu-id="b335d-103">This parameter cannot be null, empty, or consist only of whitespace.</span></span> <span data-ttu-id="b335d-104">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="b335d-104">UNC paths may also be provided.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b335d-105">新しいインスタンスを初期化、<cref name="RestoreDescription" />構造体</span><span class="sxs-lookup"><span data-stu-id="b335d-105">Initializes a new instance of the <cref name="RestoreDescription" /> structure</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String,Microsoft.ServiceFabric.Data.RestorePolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string * Microsoft.ServiceFabric.Data.RestorePolicy -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription (backupFolderPath, restorePolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="b335d-106">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b335d-106">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="b335d-107">このパラメーターを null にすることはできません、空または空白のみで構成されます。</span><span class="sxs-lookup"><span data-stu-id="b335d-107">This parameter cannot be null, empty, or consist only of whitespace.</span></span> <span data-ttu-id="b335d-108">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="b335d-108">UNC paths may also be provided.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="b335d-109">復元のポリシー。</span><span class="sxs-lookup"><span data-stu-id="b335d-109">The restore policy.</span></span></param>
        <summary>
            <span data-ttu-id="b335d-110">RestoreDescription 構造体の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b335d-110">Initializes a new instance of the RestoreDescription structure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupFolderPath">
      <MemberSignature Language="C#" Value="public string BackupFolderPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.BackupFolderPath : string" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b335d-111">レプリカの状態を復元するために使用するディレクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="b335d-111">Gets the directory which will be used to restore the replica's state.</span></span>
            <span data-ttu-id="b335d-112">このパラメーターを null にすることはできません、空または空白のみで構成されます。</span><span class="sxs-lookup"><span data-stu-id="b335d-112">This parameter cannot be null, empty, or consist only of whitespace.</span></span> <span data-ttu-id="b335d-113">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="b335d-113">UNC paths may also be provided.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b335d-114">レプリカの状態を復元するために使用するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="b335d-114">The directory which will be used to restore the replica's state.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="b335d-115">フォルダーには、完全バックアップを 1 つ以上含まれている必要があります。</span><span class="sxs-lookup"><span data-stu-id="b335d-115">Folder must at least contain one full backup.</span></span>
            <span data-ttu-id="b335d-116">さらに、1 つまたは複数の増分バックアップを含めることできます。</span><span class="sxs-lookup"><span data-stu-id="b335d-116">In addition, it could include one or more incremental backups.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.RestorePolicy Policy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.RestorePolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Policy As RestorePolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.ServiceFabric.Data.RestorePolicy" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.RestorePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b335d-117">復元のポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b335d-117">Gets the restore policy.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b335d-118">復元操作に使用するポリシー。</span><span class="sxs-lookup"><span data-stu-id="b335d-118">Policy to be used for the restore.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>