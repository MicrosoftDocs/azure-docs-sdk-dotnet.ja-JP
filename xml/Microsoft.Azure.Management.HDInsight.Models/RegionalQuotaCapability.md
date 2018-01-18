<Type Name="RegionalQuotaCapability" FullName="Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability">
  <TypeSignature Language="C#" Value="public class RegionalQuotaCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegionalQuotaCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class RegionalQuotaCapability" />
  <TypeSignature Language="F#" Value="type RegionalQuotaCapability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public RegionalQuotaCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegionalQuotaCapability (string regionName = null, Nullable&lt;long&gt; coresUsed = null, Nullable&lt;long&gt; coresAvailable = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string regionName, valuetype System.Nullable`1&lt;int64&gt; coresUsed, valuetype System.Nullable`1&lt;int64&gt; coresAvailable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.#ctor(System.String,System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional regionName As String = null, Optional coresUsed As Nullable(Of Long) = null, Optional coresAvailable As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability : string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability" Usage="new Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability (regionName, coresUsed, coresAvailable)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="regionName" Type="System.String" />
        <Parameter Name="coresUsed" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="coresAvailable" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="regionName">To be added.</param>
        <param name="coresUsed">To be added.</param>
        <param name="coresAvailable">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoresAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CoresAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CoresAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.CoresAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property CoresAvailable As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CoresAvailable : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.CoresAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cores_available")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoresUsed">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CoresUsed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CoresUsed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.CoresUsed" />
      <MemberSignature Language="VB.NET" Value="Public Property CoresUsed As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CoresUsed : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.CoresUsed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cores_used")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegionName">
      <MemberSignature Language="C#" Value="public string RegionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.RegionName" />
      <MemberSignature Language="VB.NET" Value="Public Property RegionName As String" />
      <MemberSignature Language="F#" Value="member this.RegionName : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.RegionalQuotaCapability.RegionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="region_name")</AttributeName>
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