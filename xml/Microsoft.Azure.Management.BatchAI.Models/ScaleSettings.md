<Type Name="ScaleSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.ScaleSettings">
  <TypeSignature Language="C#" Value="public class ScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleSettings" />
  <TypeSignature Language="F#" Value="type ScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81479-101">手動または自動スケール設定には、少なくとも 1 つを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="81479-101">At least one of manual or autoScale settings must be specified.</span></span> <span data-ttu-id="81479-102">手動または自動スケール設定の 1 つのみを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="81479-102">Only one of manual or autoScale settings can be specified.</span></span> <span data-ttu-id="81479-103">自動スケーリングの設定を指定する場合、システムを上下 (制限内で、指定された) に基づくクラスターのクラスターで保留中のジョブが自動的にスケーリングします。</span><span class="sxs-lookup"><span data-stu-id="81479-103">If autoScale settings are specified, the system automatically scales the cluster up and down (within the supplied limits) based on the pending jobs on the cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81479-104">ScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="81479-104">Initializes a new instance of the ScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings (Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings manual = null, Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings autoScale = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings manual, class Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings autoScale) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ScaleSettings.#ctor(Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings,Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional manual As ManualScaleSettings = null, Optional autoScale As AutoScaleSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ScaleSettings : Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings * Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings -&gt; Microsoft.Azure.Management.BatchAI.Models.ScaleSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.ScaleSettings (manual, autoScale)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="manual" Type="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings" />
        <Parameter Name="autoScale" Type="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings" />
      </Parameters>
      <Docs>
        <param name="manual"><span data-ttu-id="81479-105">手動による設定によって、クラスターのスケール</span><span class="sxs-lookup"><span data-stu-id="81479-105">The scale for the cluster by manual settings</span></span></param>
        <param name="autoScale"><span data-ttu-id="81479-106">自動スケール設定で、クラスターのスケール</span><span class="sxs-lookup"><span data-stu-id="81479-106">The scale for the cluster by autoscale settings</span></span></param>
        <summary>
            <span data-ttu-id="81479-107">ScaleSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="81479-107">Initializes a new instance of the ScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings AutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings AutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ScaleSettings.AutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScale As AutoScaleSettings" />
      <MemberSignature Language="F#" Value="member this.AutoScale : Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ScaleSettings.AutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81479-108">取得または自動スケール設定で、クラスターのスケールを設定</span><span class="sxs-lookup"><span data-stu-id="81479-108">Gets or sets the scale for the cluster by autoscale settings</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Manual">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings Manual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings Manual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ScaleSettings.Manual" />
      <MemberSignature Language="VB.NET" Value="Public Property Manual As ManualScaleSettings" />
      <MemberSignature Language="F#" Value="member this.Manual : Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ScaleSettings.Manual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="manual")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81479-109">取得または設定を手動でクラスターのスケールを設定</span><span class="sxs-lookup"><span data-stu-id="81479-109">Gets or sets the scale for the cluster by manual settings</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81479-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="81479-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81479-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81479-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>