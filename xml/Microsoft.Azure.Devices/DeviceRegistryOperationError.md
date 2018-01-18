<Type Name="DeviceRegistryOperationError" FullName="Microsoft.Azure.Devices.DeviceRegistryOperationError">
  <TypeSignature Language="C#" Value="public sealed class DeviceRegistryOperationError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceRegistryOperationError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.DeviceRegistryOperationError" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceRegistryOperationError" />
  <TypeSignature Language="F#" Value="type DeviceRegistryOperationError = class" />
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
            <span data-ttu-id="627fd-101">デバイス レジストリ操作のエラーの詳細をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="627fd-101">Encapsulates device registry operation error details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceRegistryOperationError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.DeviceRegistryOperationError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceRegistryOperationError.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.DeviceRegistryOperationError.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="deviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627fd-102">エラーが示されているデバイスの ID。</span><span class="sxs-lookup"><span data-stu-id="627fd-102">The ID of the device that indicated the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Common.Exceptions.ErrorCode ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.Common.Exceptions.ErrorCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceRegistryOperationError.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As ErrorCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.Azure.Devices.Common.Exceptions.ErrorCode with get, set" Usage="Microsoft.Azure.Devices.DeviceRegistryOperationError.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Common.Exceptions.ErrorCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627fd-103">エラーに関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="627fd-103">ErrorCode associated with the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorStatus">
      <MemberSignature Language="C#" Value="public string ErrorStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceRegistryOperationError.ErrorStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorStatus As String" />
      <MemberSignature Language="F#" Value="member this.ErrorStatus : string with get, set" Usage="Microsoft.Azure.Devices.DeviceRegistryOperationError.ErrorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="errorStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627fd-104">詳細は、エラーに関連付けられているとします。</span><span class="sxs-lookup"><span data-stu-id="627fd-104">Additional details associated with the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>