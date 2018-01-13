<Type Name="ScaleSettings" FullName="Microsoft.Azure.Management.Batch.Models.ScaleSettings">
  <TypeSignature Language="C#" Value="public class ScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleSettings" />
  <TypeSignature Language="F#" Value="type ScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="91bba-101">プールのスケール設定</span><span class="sxs-lookup"><span data-stu-id="91bba-101">Scale settings for the pool</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="91bba-102">プールの目的のサイズを定義します。</span><span class="sxs-lookup"><span data-stu-id="91bba-102">Defines the desired size of the pool.</span></span> <span data-ttu-id="91bba-103">要求された targetDedicatedNodes が指定されている ' fixedScale' または 'autoScale' を定期的に再評価する式を定義を指定できます。</span><span class="sxs-lookup"><span data-stu-id="91bba-103">This can either be 'fixedScale' where the requested targetDedicatedNodes is specified, or 'autoScale' which defines a formula which is periodically reevaluated.</span></span> <span data-ttu-id="91bba-104">このプロパティが指定されていない場合、プールに 0 targetDedicatedNodes と固定小数点以下桁数があります。</span><span class="sxs-lookup"><span data-stu-id="91bba-104">If this property is not specified, the pool will have a fixed scale with 0 targetDedicatedNodes.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="91bba-105">ScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="91bba-105">Initializes a new instance of the ScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings (Microsoft.Azure.Management.Batch.Models.FixedScaleSettings fixedScale = null, Microsoft.Azure.Management.Batch.Models.AutoScaleSettings autoScale = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.FixedScaleSettings fixedScale, class Microsoft.Azure.Management.Batch.Models.AutoScaleSettings autoScale) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.#ctor(Microsoft.Azure.Management.Batch.Models.FixedScaleSettings,Microsoft.Azure.Management.Batch.Models.AutoScaleSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional fixedScale As FixedScaleSettings = null, Optional autoScale As AutoScaleSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ScaleSettings : Microsoft.Azure.Management.Batch.Models.FixedScaleSettings * Microsoft.Azure.Management.Batch.Models.AutoScaleSettings -&gt; Microsoft.Azure.Management.Batch.Models.ScaleSettings" Usage="new Microsoft.Azure.Management.Batch.Models.ScaleSettings (fixedScale, autoScale)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fixedScale" Type="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings" />
        <Parameter Name="autoScale" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleSettings" />
      </Parameters>
      <Docs>
        <param name="fixedScale"><span data-ttu-id="91bba-106">プールのスケール設定を固定します。</span><span class="sxs-lookup"><span data-stu-id="91bba-106">Fixed scale settings for the pool.</span></span></param>
        <param name="autoScale"><span data-ttu-id="91bba-107">プールの自動スケール設定します。</span><span class="sxs-lookup"><span data-stu-id="91bba-107">AutoScale settings for the pool.</span></span></param>
        <summary>
            <span data-ttu-id="91bba-108">ScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="91bba-108">Initializes a new instance of the ScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleSettings AutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleSettings AutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ScaleSettings.AutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScale As AutoScaleSettings" />
      <MemberSignature Language="F#" Value="member this.AutoScale : Microsoft.Azure.Management.Batch.Models.AutoScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ScaleSettings.AutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91bba-109">取得またはプールの自動スケール設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="91bba-109">Gets or sets autoScale settings for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91bba-110">このプロパティと fixedScale は相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="91bba-110">This property and fixedScale are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FixedScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.FixedScaleSettings FixedScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.FixedScaleSettings FixedScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ScaleSettings.FixedScale" />
      <MemberSignature Language="VB.NET" Value="Public Property FixedScale As FixedScaleSettings" />
      <MemberSignature Language="F#" Value="member this.FixedScale : Microsoft.Azure.Management.Batch.Models.FixedScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ScaleSettings.FixedScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fixedScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.FixedScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91bba-111">取得またはプールの固定のスケール設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="91bba-111">Gets or sets fixed scale settings for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91bba-112">このプロパティと自動スケールでは、相互に排他的とプロパティのいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="91bba-112">This property and autoScale are mutually exclusive and one of the properties must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="91bba-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="91bba-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="91bba-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="91bba-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>