<Type Name="DeviceJobParameters" FullName="Microsoft.Azure.Devices.DeviceJobParameters">
  <TypeSignature Language="C#" Value="public class DeviceJobParameters : Microsoft.Azure.Devices.JobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeviceJobParameters extends Microsoft.Azure.Devices.JobParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.DeviceJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceJobParameters&#xA;Inherits JobParameters" />
  <TypeSignature Language="F#" Value="type DeviceJobParameters = class&#xA;    inherit JobParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.JobParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
                <span data-ttu-id="3cbbf-101">デバイス Id を使用して JobParameters を拡張します。</span><span class="sxs-lookup"><span data-stu-id="3cbbf-101">Extend JobParameters with device Ids</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceJobParameters (Microsoft.Azure.Devices.JobType jobType, System.Collections.Generic.IEnumerable&lt;string&gt; deviceIds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Devices.JobType jobType, class System.Collections.Generic.IEnumerable`1&lt;string&gt; deviceIds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.DeviceJobParameters.#ctor(Microsoft.Azure.Devices.JobType,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.DeviceJobParameters : Microsoft.Azure.Devices.JobType * seq&lt;string&gt; -&gt; Microsoft.Azure.Devices.DeviceJobParameters" Usage="new Microsoft.Azure.Devices.DeviceJobParameters (jobType, deviceIds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobType" Type="Microsoft.Azure.Devices.JobType" />
        <Parameter Name="deviceIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jobType">To be added.</param>
        <param name="deviceIds">To be added.</param>
        <summary>
                <span data-ttu-id="3cbbf-102">複数のデバイスでのパラメーターなしのデバイスのジョブのパラメーター</span><span class="sxs-lookup"><span data-stu-id="3cbbf-102">Parameters for parameterless device job on multiple devices</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceJobParameters (Microsoft.Azure.Devices.JobType jobType, string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Devices.JobType jobType, string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.DeviceJobParameters.#ctor(Microsoft.Azure.Devices.JobType,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.DeviceJobParameters : Microsoft.Azure.Devices.JobType * string -&gt; Microsoft.Azure.Devices.DeviceJobParameters" Usage="new Microsoft.Azure.Devices.DeviceJobParameters (jobType, deviceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobType" Type="Microsoft.Azure.Devices.JobType" />
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobType">To be added.</param>
        <param name="deviceId">To be added.</param>
        <summary>
                <span data-ttu-id="3cbbf-103">1 台のデバイスでのパラメーターなしのデバイスのジョブのパラメーター</span><span class="sxs-lookup"><span data-stu-id="3cbbf-103">Parameters for parameterless device job on a single device</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DeviceIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DeviceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceJobParameters.DeviceIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviceIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DeviceIds : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Devices.DeviceJobParameters.DeviceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="3cbbf-104">ターゲット デバイスの id</span><span class="sxs-lookup"><span data-stu-id="3cbbf-104">Ids of target devices</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>