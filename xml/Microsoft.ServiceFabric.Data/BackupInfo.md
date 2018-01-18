<Type Name="BackupInfo" FullName="Microsoft.ServiceFabric.Data.BackupInfo">
  <TypeSignature Language="C#" Value="public class BackupInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupInfo" />
  <TypeSignature Language="F#" Value="type BackupInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="18f91-101">バックアップに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="18f91-101">Provides information about the backup.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupInfo (string directory, Microsoft.ServiceFabric.Data.BackupOption option, Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string directory, valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.#ctor(System.String,Microsoft.ServiceFabric.Data.BackupOption,Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directory As String, option As BackupOption, version As BackupInfo.BackupVersion)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupInfo : string * Microsoft.ServiceFabric.Data.BackupOption * Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; Microsoft.ServiceFabric.Data.BackupInfo" Usage="new Microsoft.ServiceFabric.Data.BackupInfo (directory, option, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directory" Type="System.String" />
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="version" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
      </Parameters>
      <Docs>
        <param name="directory"><span data-ttu-id="18f91-102">バックアップを含むフォルダー パスです。</span><span class="sxs-lookup"><span data-stu-id="18f91-102">Folder path that contains the backup.</span></span></param>
        <param name="option">
          <span data-ttu-id="18f91-103"><cref name="BackupOption" />バックアップに使用されました。</span><span class="sxs-lookup"><span data-stu-id="18f91-103"><cref name="BackupOption" /> that was used to take the backup.</span></span></param>
        <param name="version">
          <span data-ttu-id="18f91-104"><cref name="BackupVersion" />バックアップ。</span><span class="sxs-lookup"><span data-stu-id="18f91-104"><cref name="BackupVersion" /> of the backup.</span></span></param>
        <summary>
            <span data-ttu-id="18f91-105"><cref name="BackupInfo" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="18f91-105">Initializes a new instance of the <cref name="BackupInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupInfo (string directory, Microsoft.ServiceFabric.Data.BackupOption option, Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion version, Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion startBackupVersion, Guid backupId, Guid parentBackupId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string directory, valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion version, valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion startBackupVersion, valuetype System.Guid backupId, valuetype System.Guid parentBackupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.#ctor(System.String,Microsoft.ServiceFabric.Data.BackupOption,Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion,Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion,System.Guid,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directory As String, option As BackupOption, version As BackupInfo.BackupVersion, startBackupVersion As BackupInfo.BackupVersion, backupId As Guid, parentBackupId As Guid)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupInfo : string * Microsoft.ServiceFabric.Data.BackupOption * Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion * Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion * Guid * Guid -&gt; Microsoft.ServiceFabric.Data.BackupInfo" Usage="new Microsoft.ServiceFabric.Data.BackupInfo (directory, option, version, startBackupVersion, backupId, parentBackupId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directory" Type="System.String" />
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="version" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
        <Parameter Name="startBackupVersion" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
        <Parameter Name="backupId" Type="System.Guid" />
        <Parameter Name="parentBackupId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="directory"><span data-ttu-id="18f91-106">バックアップを含むフォルダー パスです。</span><span class="sxs-lookup"><span data-stu-id="18f91-106">Folder path that contains the backup.</span></span></param>
        <param name="option">
          <span data-ttu-id="18f91-107"><cref name="BackupOption" />バックアップに使用されました。</span><span class="sxs-lookup"><span data-stu-id="18f91-107"><cref name="BackupOption" /> that was used to take the backup.</span></span></param>
        <param name="version">
          <span data-ttu-id="18f91-108"><cref name="BackupVersion" />バックアップ。</span><span class="sxs-lookup"><span data-stu-id="18f91-108"><cref name="BackupVersion" /> of the backup.</span></span></param>
        <param name="startBackupVersion">
          <span data-ttu-id="18f91-109"><cref name="BackupVersion" />バックアップの最初の論理ログ レコード。</span><span class="sxs-lookup"><span data-stu-id="18f91-109"><cref name="BackupVersion" /> of first logical log record in the backup.</span></span></param>
        <param name="backupId"><span data-ttu-id="18f91-110">バックアップの id です。</span><span class="sxs-lookup"><span data-stu-id="18f91-110">Id of the backup.</span></span></param>
        <param name="parentBackupId"><span data-ttu-id="18f91-111">Id、対応する完全バックアップ Guid.Empty の増分バックアップが発生した場合場合に、これは、完全バックアップ。</span><span class="sxs-lookup"><span data-stu-id="18f91-111">Id of the corresponding full backup in case of incremental backup, Guid.Empty in case this is full backup.</span></span></param>
        <summary>
            <span data-ttu-id="18f91-112"><cref name="BackupInfo" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="18f91-112">Initializes a new instance of the <cref name="BackupInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupId">
      <MemberSignature Language="C#" Value="public Guid BackupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid BackupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.BackupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupId As Guid" />
      <MemberSignature Language="F#" Value="member this.BackupId : Guid" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18f91-113">バックアップの Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="18f91-113">Gets the Backup Id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Directory">
      <MemberSignature Language="C#" Value="public string Directory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Directory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.Directory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Directory As String" />
      <MemberSignature Language="F#" Value="member this.Directory : string" Usage="Microsoft.ServiceFabric.Data.BackupInfo.Directory" />
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
            <span data-ttu-id="18f91-114">バックアップが作成されたディレクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="18f91-114">Gets the directory where the backup was created.</span></span> 
            </summary>
        <value><span data-ttu-id="18f91-115">バックアップを格納したディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="18f91-115">The directory containing the backup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Option">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupOption Option { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupOption Option" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.Option" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Option As BackupOption" />
      <MemberSignature Language="F#" Value="member this.Option : Microsoft.ServiceFabric.Data.BackupOption" Usage="Microsoft.ServiceFabric.Data.BackupInfo.Option" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18f91-116">使用するバックアップのオプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="18f91-116">Gets the backup option used.</span></span>
            </summary>
        <value><span data-ttu-id="18f91-117"><cref name="BackupOption" />バックアップの実行に使用されました。</span><span class="sxs-lookup"><span data-stu-id="18f91-117">The <cref name="BackupOption" /> that was used to take the backup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentBackupId">
      <MemberSignature Language="C#" Value="public Guid ParentBackupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid ParentBackupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.ParentBackupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ParentBackupId As Guid" />
      <MemberSignature Language="F#" Value="member this.ParentBackupId : Guid" Usage="Microsoft.ServiceFabric.Data.BackupInfo.ParentBackupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18f91-118">親のバックアップの ID を取得します</span><span class="sxs-lookup"><span data-stu-id="18f91-118">Gets the parent backup ID</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartBackupVersion">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion StartBackupVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion StartBackupVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.StartBackupVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartBackupVersion As BackupInfo.BackupVersion" />
      <MemberSignature Language="F#" Value="member this.StartBackupVersion : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="Microsoft.ServiceFabric.Data.BackupInfo.StartBackupVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18f91-119">バックアップ内の最初のエポックと LSN を取得します。</span><span class="sxs-lookup"><span data-stu-id="18f91-119">Gets the first epoch and LSN in the backup</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="backupInfo.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="18f91-120">このインスタンスを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="18f91-120">Returns a string that represents this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="18f91-121">このインスタンスを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="18f91-121">A string that represents this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As BackupInfo.BackupVersion" />
      <MemberSignature Language="F#" Value="member this.Version : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="Microsoft.ServiceFabric.Data.BackupInfo.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18f91-122">最新のエポックとバックアップに含める LSN を取得します。</span><span class="sxs-lookup"><span data-stu-id="18f91-122">Gets the latest epoch and LSN included in the backup.</span></span>
            </summary>
        <value>
          <span data-ttu-id="18f91-123"><cref name="BackupVersion" />バックアップ。</span><span class="sxs-lookup"><span data-stu-id="18f91-123"><cref name="BackupVersion" /> of the backup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>