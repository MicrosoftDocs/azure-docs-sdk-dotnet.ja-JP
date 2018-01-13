<Type Name="AzureIaaSComputeVMProtectableItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem">
  <TypeSignature Language="C#" Value="public class AzureIaaSComputeVMProtectableItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSComputeVMProtectableItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSComputeVMProtectableItem&#xA;Inherits IaaSVMProtectableItem" />
  <TypeSignature Language="F#" Value="type AzureIaaSComputeVMProtectableItem = class&#xA;    inherit IaaSVMProtectableItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Compute/virtualMachines")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            IaaS VM ワークロード固有バックアップを表す項目を Azure リソース マネージャーの仮想マシン。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMProtectableItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureIaaSComputeVMProtectableItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMProtectableItem (string backupManagementType = null, string friendlyName = null, string protectionState = null, string virtualMachineId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string friendlyName, string protectionState, string virtualMachineId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional friendlyName As String = null, Optional protectionState As String = null, Optional virtualMachineId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem : string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem (backupManagementType, friendlyName, protectionState, virtualMachineId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="virtualMachineId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupManagementType">項目をバックアップするバックアップ managemenent の型。</param>
        <param name="friendlyName">バックアップ項目の表示名。</param>
        <param name="protectionState">項目のバックアップの状態です。 使用可能な値が含まれます: '無効'、'NotProtected'、'を保護する'、'Protected'</param>
        <param name="virtualMachineId">仮想マシンの完全修飾の ARM ID です。</param>
        <summary>
            AzureIaaSComputeVMProtectableItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>