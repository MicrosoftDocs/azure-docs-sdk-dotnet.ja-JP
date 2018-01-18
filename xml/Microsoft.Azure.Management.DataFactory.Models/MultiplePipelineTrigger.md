<Type Name="MultiplePipelineTrigger" FullName="Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger">
  <TypeSignature Language="C#" Value="public class MultiplePipelineTrigger : Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiplePipelineTrigger extends Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiplePipelineTrigger&#xA;Inherits Trigger" />
  <TypeSignature Language="F#" Value="type MultiplePipelineTrigger = class&#xA;    inherit Trigger" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Trigger</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="61e57-101">パイプライン処理するトリガーの多くのモデルに 1 つをサポートするすべてのトリガーの基本クラス。</span><span class="sxs-lookup"><span data-stu-id="61e57-101">Base class for all triggers that support one to many model for trigger to pipeline.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiplePipelineTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61e57-102">MultiplePipelineTrigger クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61e57-102">Initializes a new instance of the MultiplePipelineTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiplePipelineTrigger (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string runtimeState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; pipelines = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string runtimeState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; pipelines) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional runtimeState As String = null, Optional pipelines As IList(Of TriggerPipelineReference) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger" Usage="new Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger (additionalProperties, description, runtimeState, pipelines)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="runtimeState" Type="System.String" />
        <Parameter Name="pipelines" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="61e57-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="61e57-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="61e57-104">トリガーの説明です。</span><span class="sxs-lookup"><span data-stu-id="61e57-104">Trigger description.</span></span></param>
        <param name="runtimeState"><span data-ttu-id="61e57-105">トリガーが実行されているかを示します。</span><span class="sxs-lookup"><span data-stu-id="61e57-105">Indicates if trigger is running or not.</span></span>
            <span data-ttu-id="61e57-106">トリガーで開始/停止 Api が呼び出されたときに更新されます。</span><span class="sxs-lookup"><span data-stu-id="61e57-106">Updated when Start/Stop APIs are called on the Trigger.</span></span> <span data-ttu-id="61e57-107">使用可能な値が含まれます: 'の開始'、'停止'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="61e57-107">Possible values include: 'Started', 'Stopped', 'Disabled'</span></span></param>
        <param name="pipelines"><span data-ttu-id="61e57-108">開始する必要があるパイプラインです。</span><span class="sxs-lookup"><span data-stu-id="61e57-108">Pipelines that need to be started.</span></span></param>
        <summary>
            <span data-ttu-id="61e57-109">MultiplePipelineTrigger クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61e57-109">Initializes a new instance of the MultiplePipelineTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipelines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; Pipelines { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; Pipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger.Pipelines" />
      <MemberSignature Language="VB.NET" Value="Public Property Pipelines As IList(Of TriggerPipelineReference)" />
      <MemberSignature Language="F#" Value="member this.Pipelines : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MultiplePipelineTrigger.Pipelines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61e57-110">取得または起動する必要があるパイプラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="61e57-110">Gets or sets pipelines that need to be started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>