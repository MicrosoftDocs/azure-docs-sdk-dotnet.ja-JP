<Type Name="PurgeMessageQueueResult" FullName="Microsoft.Azure.Devices.PurgeMessageQueueResult">
  <TypeSignature Language="C#" Value="public sealed class PurgeMessageQueueResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PurgeMessageQueueResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.PurgeMessageQueueResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PurgeMessageQueueResult" />
  <TypeSignature Language="F#" Value="type PurgeMessageQueueResult = class" />
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
            <span data-ttu-id="0c1e8-101">デバイスのメッセージ キューの結果は、操作を削除します。</span><span class="sxs-lookup"><span data-stu-id="0c1e8-101">Result of a device message queue purge operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PurgeMessageQueueResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.PurgeMessageQueueResult.#ctor" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.PurgeMessageQueueResult.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.PurgeMessageQueueResult.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceId", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c1e8-102">メッセージが含まれるが削除されるデバイスの ID。</span><span class="sxs-lookup"><span data-stu-id="0c1e8-102">The ID of the device whose messages are being purged.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalMessagesPurged">
      <MemberSignature Language="C#" Value="public int TotalMessagesPurged;" />
      <MemberSignature Language="ILAsm" Value=".field public int32 TotalMessagesPurged" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.PurgeMessageQueueResult.TotalMessagesPurged" />
      <MemberSignature Language="VB.NET" Value="Public TotalMessagesPurged As Integer " />
      <MemberSignature Language="F#" Value="val mutable TotalMessagesPurged : int" Usage="Microsoft.Azure.Devices.PurgeMessageQueueResult.TotalMessagesPurged" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalMessagesPurged", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c1e8-103">デバイスのキューから削除されたメッセージの合計数。</span><span class="sxs-lookup"><span data-stu-id="0c1e8-103">The total number of messages that were purged from the device's queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>