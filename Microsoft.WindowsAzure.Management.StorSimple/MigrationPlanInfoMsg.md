<Type Name="MigrationPlanInfoMsg" FullName="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg">
  <TypeSignature Language="C#" Value="public class MigrationPlanInfoMsg : Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationPlanInfoMsg extends Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationPlanInfoMsg&#xA;Inherits MigrationCommonModelFormatter" />
  <TypeSignature Language="F#" Value="type MigrationPlanInfoMsg = class&#xA;    inherit MigrationCommonModelFormatter" />
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
            ボリューム コンテナーごとの移行の計画 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlanInfoMsg (Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo migrationPlanInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo migrationPlanInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.#ctor(Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo -&gt; Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg" Usage="new Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg migrationPlanInfo" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="migrationPlanInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo" />
      </Parameters>
      <Docs>
        <param name="migrationPlanInfo">移行計画</param>
        <summary>
            サービスから返された実際のプランから、移行計画を構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssumedBandwidthInMbps">
      <MemberSignature Language="C#" Value="public int AssumedBandwidthInMbps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 AssumedBandwidthInMbps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.AssumedBandwidthInMbps" />
      <MemberSignature Language="VB.NET" Value="Public Property AssumedBandwidthInMbps As Integer" />
      <MemberSignature Language="F#" Value="member this.AssumedBandwidthInMbps : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.AssumedBandwidthInMbps" />
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
            取得または設定 (MBps) で使用可能な帯域幅、予測の計算中には
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudConfigurationName">
      <MemberSignature Language="C#" Value="public string CloudConfigurationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CloudConfigurationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.CloudConfigurationName" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudConfigurationName As String" />
      <MemberSignature Language="F#" Value="member this.CloudConfigurationName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.CloudConfigurationName" />
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
            取得または設定すると予想されるときは、ボリューム コンテナー
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EstimatedTimeForAllBackups">
      <MemberSignature Language="C#" Value="public TimeSpan EstimatedTimeForAllBackups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan EstimatedTimeForAllBackups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.EstimatedTimeForAllBackups" />
      <MemberSignature Language="VB.NET" Value="Public Property EstimatedTimeForAllBackups As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.EstimatedTimeForAllBackups : TimeSpan with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.EstimatedTimeForAllBackups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を移行する特定のボリューム コンテナーの全体のバックアップ セットの推定所要時間
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EstimatedTimeForLargestBackup">
      <MemberSignature Language="C#" Value="public TimeSpan EstimatedTimeForLargestBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan EstimatedTimeForLargestBackup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.EstimatedTimeForLargestBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property EstimatedTimeForLargestBackup As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.EstimatedTimeForLargestBackup : TimeSpan with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.EstimatedTimeForLargestBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定したボリューム コンテナー内の最大バックアップの移行の推定所要時間を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlanMessageInfo">
      <MemberSignature Language="C#" Value="public string PlanMessageInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlanMessageInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.PlanMessageInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PlanMessageInfo As String" />
      <MemberSignature Language="F#" Value="member this.PlanMessageInfo : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.PlanMessageInfo" />
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
            取得または設定の計画を見積もるときに返されるメッセージ/推奨事項
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As MigrationPlanStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            移行計画の状態
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsg.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="migrationPlanInfoMsg.ToString " />
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
            データ コンテナーごとの移行計画を目的の形式の文字列に変換します。
            </summary>
        <returns>文字列の形式を目的の形式でデータ コンテナー移行プランごと</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>