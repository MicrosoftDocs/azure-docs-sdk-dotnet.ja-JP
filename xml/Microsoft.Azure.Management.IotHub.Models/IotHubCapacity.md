<Type Name="IotHubCapacity" FullName="Microsoft.Azure.Management.IotHub.Models.IotHubCapacity">
  <TypeSignature Language="C#" Value="public class IotHubCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubCapacity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubCapacity" />
  <TypeSignature Language="F#" Value="type IotHubCapacity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f6323-101">IoT Hub 容量の情報です。</span><span class="sxs-lookup"><span data-stu-id="f6323-101">IoT Hub capacity information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubCapacity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f6323-102">IotHubCapacity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f6323-102">Initializes a new instance of the IotHubCapacity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubCapacity (Nullable&lt;long&gt; minimum = null, Nullable&lt;long&gt; maximum = null, Nullable&lt;long&gt; defaultProperty = null, Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt; scaleType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; minimum, valuetype System.Nullable`1&lt;int64&gt; maximum, valuetype System.Nullable`1&lt;int64&gt; defaultProperty, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt; scaleType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.IotHub.Models.IotHubScaleType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional minimum As Nullable(Of Long) = null, Optional maximum As Nullable(Of Long) = null, Optional defaultProperty As Nullable(Of Long) = null, Optional scaleType As Nullable(Of IotHubScaleType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IotHubCapacity : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubCapacity" Usage="new Microsoft.Azure.Management.IotHub.Models.IotHubCapacity (minimum, maximum, defaultProperty, scaleType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="defaultProperty" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="scaleType" Type="System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt;" />
      </Parameters>
      <Docs>
        <param name="minimum"><span data-ttu-id="f6323-103">単位の最小数。</span><span class="sxs-lookup"><span data-stu-id="f6323-103">The minimum number of units.</span></span></param>
        <param name="maximum"><span data-ttu-id="f6323-104">単位の最大数。</span><span class="sxs-lookup"><span data-stu-id="f6323-104">The maximum number of units.</span></span></param>
        <param name="defaultProperty"><span data-ttu-id="f6323-105">単位の既定の数。</span><span class="sxs-lookup"><span data-stu-id="f6323-105">The default number of units.</span></span></param>
        <param name="scaleType"><span data-ttu-id="f6323-106">有効になっている拡張の型。</span><span class="sxs-lookup"><span data-stu-id="f6323-106">The type of the scaling enabled.</span></span> <span data-ttu-id="f6323-107">使用可能な値が含まれます '自動'、'手動'、'None'。</span><span class="sxs-lookup"><span data-stu-id="f6323-107">Possible values include: 'Automatic', 'Manual', 'None'</span></span></param>
        <summary>
            <span data-ttu-id="f6323-108">IotHubCapacity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f6323-108">Initializes a new instance of the IotHubCapacity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DefaultProperty { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultProperty As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f6323-109">既定の単位数を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6323-109">Gets the default number of units.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Maximum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Maximum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f6323-110">単位の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6323-110">Gets the maximum number of units.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Minimum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Minimum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f6323-111">最小単位数を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6323-111">Gets the minimum number of units.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt; ScaleType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt; ScaleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.ScaleType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScaleType As Nullable(Of IotHubScaleType)" />
      <MemberSignature Language="F#" Value="member this.ScaleType : Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.ScaleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scaleType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubScaleType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6323-112">有効になっている目盛りの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6323-112">Gets the type of the scaling enabled.</span></span> <span data-ttu-id="f6323-113">使用可能な値が含まれます '自動'、'手動'、'None'。</span><span class="sxs-lookup"><span data-stu-id="f6323-113">Possible values include: 'Automatic', 'Manual', 'None'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubCapacity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="iotHubCapacity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f6323-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f6323-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f6323-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f6323-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>