<Type Name="VirtualMachineScaleSetSku" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetSku" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetSku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            使用可能な仮想マシン スケール セット sku をについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetSku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetSku (string resourceType = null, Microsoft.Azure.Management.Compute.Fluent.Models.Sku sku = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, class Microsoft.Azure.Management.Compute.Fluent.Models.Sku sku, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.#ctor(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.Sku,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku : string * Microsoft.Azure.Management.Compute.Fluent.Models.Sku * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku (resourceType, sku, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Fluent.Models.Sku" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity" />
      </Parameters>
      <Docs>
        <param name="resourceType">Sku のリソースの種類に適用されます。</param>
        <param name="sku">Sku。</param>
        <param name="capacity">拡大縮小に関する情報を使用できます。</param>
        <summary>
            VirtualMachineScaleSetSku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity Capacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capacity As VirtualMachineScaleSetSkuCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用可能な拡大縮小に関する情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Sku の対象リソースの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSku.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Sku を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>