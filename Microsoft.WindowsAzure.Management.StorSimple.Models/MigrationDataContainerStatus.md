<Type Name="MigrationDataContainerStatus" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus">
  <TypeSignature Language="C#" Value="public class MigrationDataContainerStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationDataContainerStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationDataContainerStatus" />
  <TypeSignature Language="F#" Value="type MigrationDataContainerStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7c4e-101">ボリューム コンテナー (クラウドの構成) のこのクラスを表す状態を移行します。</span><span class="sxs-lookup"><span data-stu-id="f7c4e-101">This class respresents status of volume container (Cloud Configuration) migrated.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationDataContainerStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7c4e-102">MigrationDataContainerStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7c4e-102">Initializes a new instance of the MigrationDataContainerStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt; BackupSets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt; BackupSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.BackupSets" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSets As IList(Of MigrationBackupSet)" />
      <MemberSignature Language="F#" Value="member this.BackupSets : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.BackupSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationBackupSet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c4e-103">必須。</span><span class="sxs-lookup"><span data-stu-id="f7c4e-103">Required.</span></span> <span data-ttu-id="f7c4e-104">取得または設定の指定したボリューム コンテナーに移行されるすべてのバックアップの状態</span><span class="sxs-lookup"><span data-stu-id="f7c4e-104">Gets or sets the status of all backup being migrated for the given volume container</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudConfigurationName">
      <MemberSignature Language="C#" Value="public string CloudConfigurationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CloudConfigurationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.CloudConfigurationName" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudConfigurationName As String" />
      <MemberSignature Language="F#" Value="member this.CloudConfigurationName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.CloudConfigurationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c4e-105">必須。</span><span class="sxs-lookup"><span data-stu-id="f7c4e-105">Required.</span></span> <span data-ttu-id="f7c4e-106">取得または設定、ボリューム コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="f7c4e-106">Gets or sets the name of the volume container</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageInfo">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo MessageInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo MessageInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.MessageInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageInfo As HcsMessageInfo" />
      <MemberSignature Language="F#" Value="member this.MessageInfo : Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.MessageInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c4e-107">必須。</span><span class="sxs-lookup"><span data-stu-id="f7c4e-107">Required.</span></span> <span data-ttu-id="f7c4e-108">取得または移行中にエラーが発生したときに通常のボリューム コンテナー レベルのメッセージや推奨事項を設定</span><span class="sxs-lookup"><span data-stu-id="f7c4e-108">Gets or sets the volume container level message or recommendation, usually when an error is encountered during migration</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentageCompleted">
      <MemberSignature Language="C#" Value="public int PercentageCompleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PercentageCompleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.PercentageCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentageCompleted As Integer" />
      <MemberSignature Language="F#" Value="member this.PercentageCompleted : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.PercentageCompleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c4e-109">必須。</span><span class="sxs-lookup"><span data-stu-id="f7c4e-109">Required.</span></span> <span data-ttu-id="f7c4e-110">取得または設定の移行が完了した割合</span><span class="sxs-lookup"><span data-stu-id="f7c4e-110">Gets or sets percentage of migration completed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As MigrationStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c4e-111">必須。</span><span class="sxs-lookup"><span data-stu-id="f7c4e-111">Required.</span></span> <span data-ttu-id="f7c4e-112">取得または設定の移行の状態</span><span class="sxs-lookup"><span data-stu-id="f7c4e-112">Gets or sets status of the migration</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>