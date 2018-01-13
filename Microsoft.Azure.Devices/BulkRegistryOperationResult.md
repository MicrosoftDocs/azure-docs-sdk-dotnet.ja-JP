<Type Name="BulkRegistryOperationResult" FullName="Microsoft.Azure.Devices.BulkRegistryOperationResult">
  <TypeSignature Language="C#" Value="public sealed class BulkRegistryOperationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BulkRegistryOperationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.BulkRegistryOperationResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BulkRegistryOperationResult" />
  <TypeSignature Language="F#" Value="type BulkRegistryOperationResult = class" />
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
            一括レジストリ操作の結果をカプセル化します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BulkRegistryOperationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.BulkRegistryOperationResult.#ctor" />
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
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.DeviceRegistryOperationError[] Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.DeviceRegistryOperationError[] Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.BulkRegistryOperationResult.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As DeviceRegistryOperationError()" />
      <MemberSignature Language="F#" Value="member this.Errors : Microsoft.Azure.Devices.DeviceRegistryOperationError[] with get, set" Usage="Microsoft.Azure.Devices.BulkRegistryOperationResult.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeviceRegistryOperationError[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作が成功しなかった場合、DeviceRegistryOperationError オブジェクトの配列が含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSuccessful">
      <MemberSignature Language="C#" Value="public bool IsSuccessful { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSuccessful" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.BulkRegistryOperationResult.IsSuccessful" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSuccessful As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSuccessful : bool with get, set" Usage="Microsoft.Azure.Devices.BulkRegistryOperationResult.IsSuccessful" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSuccessful", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作が正常に行われたかどうか。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>