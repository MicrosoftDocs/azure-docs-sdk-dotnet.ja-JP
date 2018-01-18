<Type Name="DataDisksGroups" FullName="Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups">
  <TypeSignature Language="C#" Value="public class DataDisksGroups" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisksGroups extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisksGroups" />
  <TypeSignature Language="F#" Value="type DataDisksGroups = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisksGroups ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisksGroups (Nullable&lt;int&gt; disksPerNode = null, string storageAccountType = null, Nullable&lt;int&gt; diskSizeGB = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; disksPerNode, string storageAccountType, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.#ctor(System.Nullable{System.Int32},System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional disksPerNode As Nullable(Of Integer) = null, Optional storageAccountType As String = null, Optional diskSizeGB As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups : Nullable&lt;int&gt; * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups" Usage="new Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups (disksPerNode, storageAccountType, diskSizeGB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="disksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccountType" Type="System.String" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="disksPerNode">To be added.</param>
        <param name="storageAccountType">To be added.</param>
        <param name="diskSizeGB">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DisksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DisksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.DisksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property DisksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DisksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.DisksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public string StorageAccountType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccountType As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : string" Usage="Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
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