<Type Name="ResourceSkuCapacity" FullName="Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity">
  <TypeSignature Language="C#" Value="public class ResourceSkuCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceSkuCapacity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceSkuCapacity" />
  <TypeSignature Language="F#" Value="type ResourceSkuCapacity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1340a-101">SKU の拡大縮小に関する情報をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="1340a-101">Describes scaling information of a SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSkuCapacity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1340a-102">ResourceSkuCapacity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1340a-102">Initializes a new instance of the ResourceSkuCapacity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSkuCapacity (Nullable&lt;long&gt; minimum = null, Nullable&lt;long&gt; maximum = null, Nullable&lt;long&gt; defaultProperty = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt; scaleType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; minimum, valuetype System.Nullable`1&lt;int64&gt; maximum, valuetype System.Nullable`1&lt;int64&gt; defaultProperty, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt; scaleType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional minimum As Nullable(Of Long) = null, Optional maximum As Nullable(Of Long) = null, Optional defaultProperty As Nullable(Of Long) = null, Optional scaleType As Nullable(Of ResourceSkuCapacityScaleType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity" Usage="new Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity (minimum, maximum, defaultProperty, scaleType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="defaultProperty" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="scaleType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt;" />
      </Parameters>
      <Docs>
        <param name="minimum"><span data-ttu-id="1340a-103">必要な最小容量。</span><span class="sxs-lookup"><span data-stu-id="1340a-103">The minimum capacity.</span></span></param>
        <param name="maximum"><span data-ttu-id="1340a-104">設定できる最大容量です。</span><span class="sxs-lookup"><span data-stu-id="1340a-104">The maximum capacity that can be set.</span></span></param>
        <param name="defaultProperty"><span data-ttu-id="1340a-105">既定の容量。</span><span class="sxs-lookup"><span data-stu-id="1340a-105">The default capacity.</span></span></param>
        <param name="scaleType"><span data-ttu-id="1340a-106">スケールの種類 sku に適用します。</span><span class="sxs-lookup"><span data-stu-id="1340a-106">The scale type applicable to the sku.</span></span>
            <span data-ttu-id="1340a-107">使用可能な値が含まれます '自動'、'手動'、'None'。</span><span class="sxs-lookup"><span data-stu-id="1340a-107">Possible values include: 'Automatic', 'Manual', 'None'</span></span></param>
        <summary>
            <span data-ttu-id="1340a-108">ResourceSkuCapacity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1340a-108">Initializes a new instance of the ResourceSkuCapacity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DefaultProperty { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultProperty As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="default")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1340a-109">既定の容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="1340a-109">Gets the default capacity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Maximum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Maximum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1340a-110">設定できる最大容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="1340a-110">Gets the maximum capacity that can be set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Minimum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Minimum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1340a-111">必要な最小容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="1340a-111">Gets the minimum capacity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt; ScaleType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt; ScaleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.ScaleType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScaleType As Nullable(Of ResourceSkuCapacityScaleType)" />
      <MemberSignature Language="F#" Value="member this.ScaleType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacity.ScaleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scaleType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuCapacityScaleType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1340a-112">Sku に適用可能なスケールの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="1340a-112">Gets the scale type applicable to the sku.</span></span> <span data-ttu-id="1340a-113">使用可能な値が含まれます '自動'、'手動'、'None'。</span><span class="sxs-lookup"><span data-stu-id="1340a-113">Possible values include: 'Automatic', 'Manual', 'None'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>