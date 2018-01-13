<Type Name="DeviceFailoverOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceFailoverOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceFailoverOperationsExtensions = class" />
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
    <Member MemberName="ListDCGroups">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse ListDCGroups (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse ListDCGroups(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroups(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListDCGroups : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroups (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。
            </param>
        <param name="customRequestHeaders">
            省略可能。
            </param>
        <summary>To be added.</summary>
        <returns>
            DataContainerGroups Get 呼び出しの応答のモデルを表します
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDCGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroupsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListDCGroupsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroupsAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。
            </param>
        <param name="customRequestHeaders">
            省略可能。
            </param>
        <summary>To be added.</summary>
        <returns>
            DataContainerGroups Get 呼び出しの応答のモデルを表します
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.Trigger(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.Trigger (operations, deviceId, drRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="drRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス識別子
            </param>
        <param name="drRequest">
            必須。 デバイスのフェールオーバーの要求の詳細。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            デバイスのフェールオーバーをトリガーします。
            </summary>
        <returns>
            これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.TriggerAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.TriggerAsync (operations, deviceId, drRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="drRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイス識別子
            </param>
        <param name="drRequest">
            必須。 デバイスのフェールオーバーの要求の詳細。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            デバイスのフェールオーバーをトリガーします。
            </summary>
        <returns>
            これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>