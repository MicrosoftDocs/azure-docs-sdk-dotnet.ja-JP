<Type Name="ConfirmMigrationStatus" FullName="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus">
  <TypeSignature Language="C#" Value="public class ConfirmMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConfirmMigrationStatus extends Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class ConfirmMigrationStatus&#xA;Inherits MigrationCommonModelFormatter" />
  <TypeSignature Language="F#" Value="type ConfirmMigrationStatus = class&#xA;    inherit MigrationCommonModelFormatter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスには、特定の MigrationVolumeContainerConfirmStatus ステータス内のすべてのデータ コンテナーの一覧の ConfirmStatus を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfirmMigrationStatus (Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.MigrationVolumeContainerConfirmStatus statusType, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus overallStatus);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus/MigrationVolumeContainerConfirmStatus statusType, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus overallStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.#ctor(Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.MigrationVolumeContainerConfirmStatus,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (statusType As ConfirmMigrationStatus.MigrationVolumeContainerConfirmStatus, overallStatus As MigrationConfirmStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.MigrationVolumeContainerConfirmStatus * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus -&gt; Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus" Usage="new Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus (statusType, overallStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="statusType" Type="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus+MigrationVolumeContainerConfirmStatus" />
        <Parameter Name="overallStatus" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus" />
      </Parameters>
      <Docs>
        <param name="statusType">MigrationStatus のリストの格納</param>
        <param name="overallStatus">移行の全体的な状態</param>
        <summary>
            コンストラクト ConfirmMigrationStatus オブジェクトのコンス トラクターに指定された statusType overallstatus 表示された一覧からフィルターで指定します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfirmStatus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus&gt; ConfirmStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus&gt; ConfirmStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.ConfirmStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfirmStatus As List(Of MigrationContainerConfirmStatus)" />
      <MemberSignature Language="F#" Value="member this.ConfirmStatus : System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.ConfirmStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定でボリューム コンテナーの状態を確認の一覧は、状態の確認を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.MigrationVolumeContainerConfirmStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus/MigrationVolumeContainerConfirmStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As ConfirmMigrationStatus.MigrationVolumeContainerConfirmStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.MigrationVolumeContainerConfirmStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus+MigrationVolumeContainerConfirmStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の確認の移行の状態
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="confirmMigrationStatus.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            表示する目的の形式の内容をオーバーライドします。
            </summary>
        <returns>目的の形式での移行状態の確認を表す文字列</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>