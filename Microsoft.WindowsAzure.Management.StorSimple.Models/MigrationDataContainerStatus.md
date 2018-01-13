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
            ボリューム コンテナー (クラウドの構成) のこのクラスを表す状態を移行します。
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
            MigrationDataContainerStatus クラスの新しいインスタンスを初期化します。
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
            必須。 取得または設定の指定したボリューム コンテナーに移行されるすべてのバックアップの状態
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
            必須。 取得または設定、ボリューム コンテナーの名前
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
            必須。 取得または移行中にエラーが発生したときに通常のボリューム コンテナー レベルのメッセージや推奨事項を設定
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
            必須。 取得または設定の移行が完了した割合
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
            必須。 取得または設定の移行の状態
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>