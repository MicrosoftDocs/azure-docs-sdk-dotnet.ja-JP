<Type Name="VirtualDeviceProvisioningInfo" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo">
  <TypeSignature Language="C#" Value="public class VirtualDeviceProvisioningInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualDeviceProvisioningInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualDeviceProvisioningInfo" />
  <TypeSignature Language="F#" Value="type VirtualDeviceProvisioningInfo = class" />
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
            プロビジョニングされる仮想アプライアンスに関する情報
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualDeviceProvisioningInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualDeviceProvisioningInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNewStorageAccount">
      <MemberSignature Language="C#" Value="public bool CreateNewStorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CreateNewStorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.CreateNewStorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateNewStorageAccount As Boolean" />
      <MemberSignature Language="F#" Value="member this.CreateNewStorageAccount : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.CreateNewStorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 新しいストレージ アカウントを作成または指定されたストレージ アカウントを使用するかどうかを表すブール値。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAzureCisVMOnFailure">
      <MemberSignature Language="C#" Value="public bool DeleteAzureCisVMOnFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DeleteAzureCisVMOnFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.DeleteAzureCisVMOnFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property DeleteAzureCisVMOnFailure As Boolean" />
      <MemberSignature Language="F#" Value="member this.DeleteAzureCisVMOnFailure : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.DeleteAzureCisVMOnFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 目的をデバッグするためには、エラー発生時に Azure VM を保持するブール値。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceName">
      <MemberSignature Language="C#" Value="public string DeviceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.DeviceName" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceName As String" />
      <MemberSignature Language="F#" Value="member this.DeviceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.DeviceName" />
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
            必須。 デバイスの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnWorkflowId">
      <MemberSignature Language="C#" Value="public bool ReturnWorkflowId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReturnWorkflowId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.ReturnWorkflowId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnWorkflowId As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReturnWorkflowId : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.ReturnWorkflowId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 か、ジョブを追跡するために WorkflowId を返すかどうかを表すブール値
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountName">
      <MemberSignature Language="C#" Value="public string StorageAccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.StorageAccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountName As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.StorageAccountName" />
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
            省略可能。 ストレージ アカウントの名前。 CreateNewStorageAccount が true の場合、この機能が必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubNetName">
      <MemberSignature Language="C#" Value="public string SubNetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubNetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.SubNetName" />
      <MemberSignature Language="VB.NET" Value="Public Property SubNetName As String" />
      <MemberSignature Language="F#" Value="member this.SubNetName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.SubNetName" />
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
            必須。 Net sub の名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.SubscriptionId" />
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
            必須。 サブスクリプションの識別子です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkName">
      <MemberSignature Language="C#" Value="public string VirtualNetworkName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualNetworkName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.VirtualNetworkName" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkName As String" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo.VirtualNetworkName" />
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
            必須。 仮想ネットワークの名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>