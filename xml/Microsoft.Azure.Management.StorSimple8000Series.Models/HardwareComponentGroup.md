<Type Name="HardwareComponentGroup" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup">
  <TypeSignature Language="C#" Value="public class HardwareComponentGroup : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HardwareComponentGroup extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class HardwareComponentGroup&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type HardwareComponentGroup = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3588c-101">ハードウェア コンポーネントのグループです。</span><span class="sxs-lookup"><span data-stu-id="3588c-101">The hardware component group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HardwareComponentGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3588c-102">HardwareComponentGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3588c-102">Initializes a new instance of the HardwareComponentGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HardwareComponentGroup (string displayName, DateTime lastUpdatedTime, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt; components, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string displayName, valuetype System.DateTime lastUpdatedTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt; components, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.#ctor(System.String,System.DateTime,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (displayName As String, lastUpdatedTime As DateTime, components As IList(Of HardwareComponent), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup : string * DateTime * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup (displayName, lastUpdatedTime, components, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
        <Parameter Name="components" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="displayName"><span data-ttu-id="3588c-103">ハードウェア コンポーネント グループの名前を表示します。</span><span class="sxs-lookup"><span data-stu-id="3588c-103">The display name the hardware component group.</span></span></param>
        <param name="lastUpdatedTime"><span data-ttu-id="3588c-104">最後には、時間が更新されます。</span><span class="sxs-lookup"><span data-stu-id="3588c-104">The last updated time.</span></span></param>
        <param name="components"><span data-ttu-id="3588c-105">ハードウェア コンポーネントの一覧。</span><span class="sxs-lookup"><span data-stu-id="3588c-105">The list of hardware components.</span></span></param>
        <param name="id"><span data-ttu-id="3588c-106">オブジェクトを一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="3588c-106">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="3588c-107">オブジェクトの名前。</span><span class="sxs-lookup"><span data-stu-id="3588c-107">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="3588c-108">オブジェクトの階層型です。</span><span class="sxs-lookup"><span data-stu-id="3588c-108">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="3588c-109">オブジェクトの種類。</span><span class="sxs-lookup"><span data-stu-id="3588c-109">The Kind of the object.</span></span> <span data-ttu-id="3588c-110">現在は Series8000 はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="3588c-110">Currently only Series8000 is supported.</span></span> <span data-ttu-id="3588c-111">使用可能な値が含まれます: 'Series8000'</span><span class="sxs-lookup"><span data-stu-id="3588c-111">Possible values include: 'Series8000'</span></span></param>
        <summary>
            <span data-ttu-id="3588c-112">HardwareComponentGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3588c-112">Initializes a new instance of the HardwareComponentGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Components">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt; Components { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt; Components" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.Components" />
      <MemberSignature Language="VB.NET" Value="Public Property Components As IList(Of HardwareComponent)" />
      <MemberSignature Language="F#" Value="member this.Components : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.Components" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.components")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3588c-113">取得またはハードウェア コンポーネントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="3588c-113">Gets or sets the list of hardware components.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3588c-114">取得または表示名、ハードウェア コンポーネント グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="3588c-114">Gets or sets the display name the hardware component group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.LastUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdatedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.LastUpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastUpdatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3588c-115">取得または最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="3588c-115">Gets or sets the last updated time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="hardwareComponentGroup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3588c-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3588c-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3588c-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3588c-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>