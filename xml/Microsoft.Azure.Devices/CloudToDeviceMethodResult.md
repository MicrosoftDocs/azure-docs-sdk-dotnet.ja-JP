<Type Name="CloudToDeviceMethodResult" FullName="Microsoft.Azure.Devices.CloudToDeviceMethodResult">
  <TypeSignature Language="C#" Value="public class CloudToDeviceMethodResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudToDeviceMethodResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.CloudToDeviceMethodResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudToDeviceMethodResult" />
  <TypeSignature Language="F#" Value="type CloudToDeviceMethodResult = class" />
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
            <span data-ttu-id="04158-101">デバイスのメソッド呼び出しの結果を表します。</span><span class="sxs-lookup"><span data-stu-id="04158-101">Represents the Device Method Invocation Results.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudToDeviceMethodResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.CloudToDeviceMethodResult.#ctor" />
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
    <Member MemberName="GetPayloadAsJson">
      <MemberSignature Language="C#" Value="public string GetPayloadAsJson ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetPayloadAsJson() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.CloudToDeviceMethodResult.GetPayloadAsJson" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPayloadAsJson () As String" />
      <MemberSignature Language="F#" Value="member this.GetPayloadAsJson : unit -&gt; string" Usage="cloudToDeviceMethodResult.GetPayloadAsJson " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04158-102">Json としてペイロードを取得します。</span><span class="sxs-lookup"><span data-stu-id="04158-102">Get payload as json</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public int Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.CloudToDeviceMethodResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Integer" />
      <MemberSignature Language="F#" Value="member this.Status : int with get, set" Usage="Microsoft.Azure.Devices.CloudToDeviceMethodResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04158-103">取得またはデバイス メソッドの呼び出しの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="04158-103">Gets or sets the status of device method invocation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>