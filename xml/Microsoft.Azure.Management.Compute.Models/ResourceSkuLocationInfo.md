<Type Name="ResourceSkuLocationInfo" FullName="Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo">
  <TypeSignature Language="C#" Value="public class ResourceSkuLocationInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceSkuLocationInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceSkuLocationInfo" />
  <TypeSignature Language="F#" Value="type ResourceSkuLocationInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public ResourceSkuLocationInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e72e-101">ResourceSkuLocationInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e72e-101">Initializes a new instance of the ResourceSkuLocationInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSkuLocationInfo (string location = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional zones As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo" Usage="new Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo (location, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="6e72e-102">SKU の場所</span><span class="sxs-lookup"><span data-stu-id="6e72e-102">Location of the SKU</span></span></param>
        <param name="zones"><span data-ttu-id="6e72e-103">SKU がサポートされている可用性ゾーンの一覧です。</span><span class="sxs-lookup"><span data-stu-id="6e72e-103">List of availability zones where the SKU is supported.</span></span></param>
        <summary>
            <span data-ttu-id="6e72e-104">ResourceSkuLocationInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e72e-104">Initializes a new instance of the ResourceSkuLocationInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e72e-105">SKU の場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e72e-105">Gets location of the SKU</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo.Zones" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuLocationInfo.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e72e-106">SKU がサポートされている可用性ゾーンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e72e-106">Gets list of availability zones where the SKU is supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>