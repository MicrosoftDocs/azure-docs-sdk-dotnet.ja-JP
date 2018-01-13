<Type Name="ConfirmMigrationStatusMsg" FullName="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg">
  <TypeSignature Language="C#" Value="public class ConfirmMigrationStatusMsg" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConfirmMigrationStatusMsg extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg" />
  <TypeSignature Language="VB.NET" Value="Public Class ConfirmMigrationStatusMsg" />
  <TypeSignature Language="F#" Value="type ConfirmMigrationStatusMsg = class" />
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
            特定の構成の全体的な移行の確認状態メッセージ
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfirmMigrationStatusMsg (string configID, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus overallStatus);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configID, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus overallStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.#ctor(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configID As String, overallStatus As MigrationConfirmStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg : string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus -&gt; Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg" Usage="new Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg (configID, overallStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configID" Type="System.String" />
        <Parameter Name="overallStatus" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus" />
      </Parameters>
      <Docs>
        <param name="configID">構成 id</param>
        <param name="overallStatus">移行の全体的な状態</param>
        <summary>
            Get AzureStorSimpleVolumeContainerConfirmStatus コマンドレットの出力として返される ConfirmMigrationStatusMsg を構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitComplete">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property CommitComplete As ConfirmMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.CommitComplete : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の全体的な状態の完了をコミットにボリューム コンテナーのボリューム コンテナーの状態の確認
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitFailed">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitFailed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitFailed" />
      <MemberSignature Language="VB.NET" Value="Public Property CommitFailed As ConfirmMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.CommitFailed : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            状態の取得または設定の全体的な確認のコミットにボリューム コンテナーのボリューム コンテナーの状態が失敗しました
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property CommitInProgress As ConfirmMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.CommitInProgress : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の全体的なコミット inprogress の状態でボリューム コンテナーのボリューム コンテナーの状態の確認
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitOrRollbackNotStarted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitOrRollbackNotStarted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus CommitOrRollbackNotStarted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitOrRollbackNotStarted" />
      <MemberSignature Language="VB.NET" Value="Public Property CommitOrRollbackNotStarted As ConfirmMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.CommitOrRollbackNotStarted : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.CommitOrRollbackNotStarted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の全体的なは、コミットまたはロールバックにボリューム コンテナーのボリューム コンテナーの状態が開始されていないことを確認の状態します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LegacyConfigId">
      <MemberSignature Language="C#" Value="public string LegacyConfigId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LegacyConfigId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.LegacyConfigId" />
      <MemberSignature Language="VB.NET" Value="Public Property LegacyConfigId As String" />
      <MemberSignature Language="F#" Value="member this.LegacyConfigId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.LegacyConfigId" />
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
            取得または設定がボリューム コンテナーは、状態がフェッチされることを確認構成 id
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackComplete">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus RollbackComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus RollbackComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.RollbackComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property RollbackComplete As ConfirmMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.RollbackComplete : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.RollbackComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の全体的なは、ロールバックにボリューム コンテナーのボリューム コンテナーの状態が完了したことを確認の状態します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackFailed">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus RollbackFailed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus RollbackFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.RollbackFailed" />
      <MemberSignature Language="VB.NET" Value="Public Property RollbackFailed As ConfirmMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.RollbackFailed : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.RollbackFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            状態の取得または設定の全体的な確認ロールバックでボリューム コンテナーのボリューム コンテナーの状態が失敗しました
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus RollbackInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus RollbackInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.RollbackInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property RollbackInProgress As ConfirmMigrationStatus" />
      <MemberSignature Language="F#" Value="member this.RollbackInProgress : Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatusMsg.RollbackInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ConfirmMigrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の全体的なロールバック処理中の状態でボリューム コンテナーのボリューム コンテナーの状態の確認
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>