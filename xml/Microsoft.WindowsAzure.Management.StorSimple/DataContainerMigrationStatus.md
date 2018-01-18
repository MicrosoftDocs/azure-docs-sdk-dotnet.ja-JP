<Type Name="DataContainerMigrationStatus" FullName="Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus">
  <TypeSignature Language="C#" Value="public class DataContainerMigrationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataContainerMigrationStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class DataContainerMigrationStatus" />
  <TypeSignature Language="F#" Value="type DataContainerMigrationStatus = class" />
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
            <span data-ttu-id="362dd-101">特定の構成によってインポートされたコンテナーのボリューム コンテナーの移行状況</span><span class="sxs-lookup"><span data-stu-id="362dd-101">Volume container migration status for the containers imported by the specific config</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataContainerMigrationStatus (string configId, System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; overallStatusList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configId, class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; overallStatusList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.#ctor(System.String,System.Collections.Generic.List{Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configId As String, overallStatusList As List(Of MigrationDataContainerStatus))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus : string * System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; -&gt; Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus" Usage="new Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus (configId, overallStatusList)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="overallStatusList" Type="System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="configId"><span data-ttu-id="362dd-102">移行の現在のインスタンスに対応する ConfigId</span><span class="sxs-lookup"><span data-stu-id="362dd-102">ConfigId corresponding to current instance of migration</span></span></param>
        <param name="overallStatusList"><span data-ttu-id="362dd-103">サービスから取得した状態の全体的な一覧</span><span class="sxs-lookup"><span data-stu-id="362dd-103">Overall list of status obtained from service</span></span></param>
        <summary>
            <span data-ttu-id="362dd-104">ボリューム コンテナーの移行状態の全体的なオブジェクトを構築します。</span><span class="sxs-lookup"><span data-stu-id="362dd-104">Constructs the overall volume container migration status object</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LegacyConfigId">
      <MemberSignature Language="C#" Value="public string LegacyConfigId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LegacyConfigId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.LegacyConfigId" />
      <MemberSignature Language="VB.NET" Value="Public Property LegacyConfigId As String" />
      <MemberSignature Language="F#" Value="member this.LegacyConfigId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.LegacyConfigId" />
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
            <span data-ttu-id="362dd-105">取得または設定がボリューム コンテナーは、状態がフェッチされることを確認構成 id</span><span class="sxs-lookup"><span data-stu-id="362dd-105">Gets or sets the config id whose volume container confirm status is fetched</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationCompleted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationCompleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationCompleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationCompleted As LegacyDataContainerMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.MigrationCompleted : Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationCompleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="362dd-106">取得または設定の移行状態の一覧が MigrationState が完了したすべてのボリューム コンテナー</span><span class="sxs-lookup"><span data-stu-id="362dd-106">Gets or sets the list of migration state for all volume containers whose MigrationState is Completed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationFailed">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationFailed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationFailed" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationFailed As LegacyDataContainerMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.MigrationFailed : Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="362dd-107">取得または設定の移行状態の一覧が MigrationState に失敗しましたが、すべてのボリューム コンテナー</span><span class="sxs-lookup"><span data-stu-id="362dd-107">Gets or sets the list of migration state for all volume containers whose MigrationState is Failed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationInprogress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationInprogress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationInprogress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationInprogress" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationInprogress As LegacyDataContainerMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.MigrationInprogress : Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationInprogress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="362dd-108">取得または設定の移行状態の一覧が MigrationState は処理中のすべてのボリューム コンテナー</span><span class="sxs-lookup"><span data-stu-id="362dd-108">Gets or sets the list of migration state for all volume containers whose MigrationState is InProgress</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationNotStarted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationNotStarted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus MigrationNotStarted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationNotStarted" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationNotStarted As LegacyDataContainerMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.MigrationNotStarted : Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerMigrationStatus.MigrationNotStarted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="362dd-109">取得または設定の移行状態の一覧が MigrationState NotStarted は、すべてのボリューム コンテナー</span><span class="sxs-lookup"><span data-stu-id="362dd-109">Gets or sets the list of migration state for all volume containers whose MigrationState is NotStarted</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>