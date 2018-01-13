<Type Name="VirtualDeviceOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualDeviceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualDeviceOperationsExtensions = class" />
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
            これは、StorSimple のオブジェクトを管理する rest ベースの API
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Create (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Create(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.Create (operations, virtualDeviceProvisioningInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" RefType="this" />
        <Parameter Name="virtualDeviceProvisioningInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations への参照。
            </param>
        <param name="virtualDeviceProvisioningInfo">
            必須。 仮想デバイスのプロビジョニング情報です。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            仮想デバイスの作成
            </summary>
        <returns>
            これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.CreateAsync (operations, virtualDeviceProvisioningInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" RefType="this" />
        <Parameter Name="virtualDeviceProvisioningInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations への参照。
            </param>
        <param name="virtualDeviceProvisioningInfo">
            必須。 仮想デバイスのプロビジョニング情報です。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            仮想デバイスの作成
            </summary>
        <returns>
            これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>