<Type Name="MigrationPlanInfo" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo">
  <TypeSignature Language="C#" Value="public class MigrationPlanInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationPlanInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationPlanInfo" />
  <TypeSignature Language="F#" Value="type MigrationPlanInfo = class" />
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
            特定のデータ コンテナーの移行計画
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlanInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MigrationPlanInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssumedBandwidthInMbps">
      <MemberSignature Language="C#" Value="public int AssumedBandwidthInMbps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 AssumedBandwidthInMbps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.AssumedBandwidthInMbps" />
      <MemberSignature Language="VB.NET" Value="Public Property AssumedBandwidthInMbps As Integer" />
      <MemberSignature Language="F#" Value="member this.AssumedBandwidthInMbps : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.AssumedBandwidthInMbps" />
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
            必須。 取得または MBps での移行時間を計算するために想定帯域幅の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainerName">
      <MemberSignature Language="C#" Value="public string DataContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.DataContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainerName As String" />
      <MemberSignature Language="F#" Value="member this.DataContainerName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.DataContainerName" />
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
            必須。 取得または設定データ コンテナーの名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EstimatedTimeInMinutes">
      <MemberSignature Language="C#" Value="public int EstimatedTimeInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 EstimatedTimeInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.EstimatedTimeInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property EstimatedTimeInMinutes As Integer" />
      <MemberSignature Language="F#" Value="member this.EstimatedTimeInMinutes : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.EstimatedTimeInMinutes" />
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
            必須。 取得または設定のすべての推定所要時間 (分単位) を移行するバックアップ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EstimatedTimeInMinutesForLargestBackup">
      <MemberSignature Language="C#" Value="public int EstimatedTimeInMinutesForLargestBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 EstimatedTimeInMinutesForLargestBackup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.EstimatedTimeInMinutesForLargestBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property EstimatedTimeInMinutesForLargestBackup As Integer" />
      <MemberSignature Language="F#" Value="member this.EstimatedTimeInMinutesForLargestBackup : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.EstimatedTimeInMinutesForLargestBackup" />
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
            必須。 取得または設定 (分単位) を移行する最も大きなバックアップの推定所要時間
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlanMessageInfoList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt; PlanMessageInfoList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt; PlanMessageInfoList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.PlanMessageInfoList" />
      <MemberSignature Language="VB.NET" Value="Public Property PlanMessageInfoList As IList(Of HcsMessageInfo)" />
      <MemberSignature Language="F#" Value="member this.PlanMessageInfoList : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.PlanMessageInfoList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 取得または設定一覧メッセージおよび実行されている見積もりに基づいて返される推奨事項
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlanStatus">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStatus PlanStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStatus PlanStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.PlanStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property PlanStatus As MigrationPlanStatus" />
      <MemberSignature Language="F#" Value="member this.PlanStatus : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanInfo.PlanStatus" />
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
            必須。 取得または設定の移行計画の状態
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>