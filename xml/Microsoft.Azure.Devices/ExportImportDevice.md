<Type Name="ExportImportDevice" FullName="Microsoft.Azure.Devices.ExportImportDevice">
  <TypeSignature Language="C#" Value="public sealed class ExportImportDevice" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExportImportDevice extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.ExportImportDevice" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExportImportDevice" />
  <TypeSignature Language="F#" Value="type ExportImportDevice = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="91870-101">エクスポート/インポート操作中に指定されているデバイス プロパティが含まれています</span><span class="sxs-lookup"><span data-stu-id="91870-101">contains device properties specified during export/import operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportImportDevice ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ExportImportDevice.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="91870-102">既定のコンス トラクターをパブリックにすること</span><span class="sxs-lookup"><span data-stu-id="91870-102">making default ctor public</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportImportDevice (Microsoft.Azure.Devices.Device device, Microsoft.Azure.Devices.ImportMode importmode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Devices.Device device, valuetype Microsoft.Azure.Devices.ImportMode importmode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ExportImportDevice.#ctor(Microsoft.Azure.Devices.Device,Microsoft.Azure.Devices.ImportMode)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.ExportImportDevice : Microsoft.Azure.Devices.Device * Microsoft.Azure.Devices.ImportMode -&gt; Microsoft.Azure.Devices.ExportImportDevice" Usage="new Microsoft.Azure.Devices.ExportImportDevice (device, importmode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="importmode" Type="Microsoft.Azure.Devices.ImportMode" />
      </Parameters>
      <Docs>
        <param name="device"></param>
        <param name="importmode"></param>
        <summary>
            <span data-ttu-id="91870-103">インポート モードと共にデバイス オブジェクトを受け取る ctor</span><span class="sxs-lookup"><span data-stu-id="91870-103">ctor which takes a Device object along with import mode</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.AuthenticationMechanism Authentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.AuthenticationMechanism Authentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.Authentication" />
      <MemberSignature Language="VB.NET" Value="Public Property Authentication As AuthenticationMechanism" />
      <MemberSignature Language="F#" Value="member this.Authentication : Microsoft.Azure.Devices.AuthenticationMechanism with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.Authentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.AuthenticationMechanism</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91870-104">デバイスの AuthenticationMechanism</span><span class="sxs-lookup"><span data-stu-id="91870-104">AuthenticationMechanism of the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91870-105">デバイスの ETag です。</span><span class="sxs-lookup"><span data-stu-id="91870-105">ETag of the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91870-106">デバイスの ID</span><span class="sxs-lookup"><span data-stu-id="91870-106">Id of the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.ImportMode ImportMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.ImportMode ImportMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.ImportMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ImportMode As ImportMode" />
      <MemberSignature Language="F#" Value="member this.ImportMode : Microsoft.Azure.Devices.ImportMode with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.ImportMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate, PropertyName="importMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.ImportMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91870-107">デバイスの ImportMode</span><span class="sxs-lookup"><span data-stu-id="91870-107">ImportMode of the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.ExportImportDevice.PropertyContainer Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.ExportImportDevice/PropertyContainer Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ExportImportDevice.PropertyContainer" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Devices.ExportImportDevice.PropertyContainer with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.ExportImportDevice+PropertyContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.DeviceStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.DeviceStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As DeviceStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Devices.DeviceStatus with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeviceStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91870-108">デバイスの状態</span><span class="sxs-lookup"><span data-stu-id="91870-108">Status of the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusReason">
      <MemberSignature Language="C#" Value="public string StatusReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.StatusReason" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusReason As String" />
      <MemberSignature Language="F#" Value="member this.StatusReason : string with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.StatusReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="statusReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91870-109">デバイスのステータス</span><span class="sxs-lookup"><span data-stu-id="91870-109">StatusReason of the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Shared.TwinCollection Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Shared.TwinCollection Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As TwinCollection" />
      <MemberSignature Language="F#" Value="member this.Tags : Microsoft.Azure.Devices.Shared.TwinCollection with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.TwinCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TwinETag">
      <MemberSignature Language="C#" Value="public string TwinETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TwinETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.ExportImportDevice.TwinETag" />
      <MemberSignature Language="VB.NET" Value="Public Property TwinETag As String" />
      <MemberSignature Language="F#" Value="member this.TwinETag : string with get, set" Usage="Microsoft.Azure.Devices.ExportImportDevice.TwinETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="twinETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>