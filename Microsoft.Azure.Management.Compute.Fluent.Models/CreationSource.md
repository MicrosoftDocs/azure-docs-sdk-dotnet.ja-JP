<Type Name="CreationSource" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource">
  <TypeSignature Language="C#" Value="public class CreationSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreationSource extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource" />
  <TypeSignature Language="VB.NET" Value="Public Class CreationSource" />
  <TypeSignature Language="F#" Value="type CreationSource = class" />
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
             管理対象ディスク/スナップショットの作成元のソースです。
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationSource (Microsoft.Azure.Management.Compute.Fluent.Models.CreationData creationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.CreationData creationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.CreationData)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource : Microsoft.Azure.Management.Compute.Fluent.Models.CreationData -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource creationData" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="creationData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData" />
      </Parameters>
      <Docs>
        <param name="creationData">管理対象ディスク/スナップショットの作成データ。</param>
        <summary>
             DiskSource を作成します。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDataDiskImageLun">
      <MemberSignature Language="C#" Value="public int SourceDataDiskImageLun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 SourceDataDiskImageLun() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.SourceDataDiskImageLun" />
      <MemberSignature Language="VB.NET" Value="Public Function SourceDataDiskImageLun () As Integer" />
      <MemberSignature Language="F#" Value="member this.SourceDataDiskImageLun : unit -&gt; int" Usage="creationSource.SourceDataDiskImageLun " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
             このディスクまたはスナップショットが作成された場合、データのディスク イメージを-1 からそれ以外の場合は、データ ディスクのイメージの lun 値。
             </return>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string SourceId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public Function SourceId () As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : unit -&gt; string" Usage="creationSource.SourceId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ソースの id です。</return>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As CreationSourceType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return>ディスクまたはスナップショットの作成元のソースの種類。</return>
      </Docs>
    </Member>
  </Members>
</Type>