<Type Name="VirtualMachineScaleSetStorageProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetStorageProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetStorageProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetStorageProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetStorageProfile = class" />
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
            仮想マシン スケール セットのストレージ プロファイルをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetStorageProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetStorageProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetStorageProfile (Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner imageReference = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk osDisk = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt; dataDisks = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner imageReference, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk osDisk, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt; dataDisks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional imageReference As ImageReferenceInner = null, Optional osDisk As VirtualMachineScaleSetOSDisk = null, Optional dataDisks As IList(Of VirtualMachineScaleSetDataDisk) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile (imageReference, osDisk, dataDisks)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="imageReference">イメージの参照。</param>
        <param name="osDisk">OS ディスクです。</param>
        <param name="dataDisks">データ ディスク。</param>
        <summary>
            VirtualMachineScaleSetStorageProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of VirtualMachineScaleSetDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ディスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReferenceInner" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または画像の参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As VirtualMachineScaleSetOSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OS ディスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetStorageProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>