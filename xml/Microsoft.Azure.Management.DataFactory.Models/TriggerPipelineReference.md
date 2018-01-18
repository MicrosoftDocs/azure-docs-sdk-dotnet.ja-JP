<Type Name="TriggerPipelineReference" FullName="Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference">
  <TypeSignature Language="C#" Value="public class TriggerPipelineReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggerPipelineReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggerPipelineReference" />
  <TypeSignature Language="F#" Value="type TriggerPipelineReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8bb8c-101">指定されたパラメーターを使用してトリガーする必要があるパイプラインです。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-101">Pipeline that needs to be triggered with the given parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerPipelineReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8bb8c-102">TriggerPipelineReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-102">Initializes a new instance of the TriggerPipelineReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerPipelineReference (Microsoft.Azure.Management.DataFactory.Models.PipelineReference pipelineReference = null, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.PipelineReference pipelineReference, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference.#ctor(Microsoft.Azure.Management.DataFactory.Models.PipelineReference,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference : Microsoft.Azure.Management.DataFactory.Models.PipelineReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference" Usage="new Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference (pipelineReference, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pipelineReference" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineReference" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="pipelineReference"><span data-ttu-id="8bb8c-103">パイプラインの参照。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-103">Pipeline reference.</span></span></param>
        <param name="parameters"><span data-ttu-id="8bb8c-104">パイプラインのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-104">Pipeline parameters.</span></span></param>
        <summary>
            <span data-ttu-id="8bb8c-105">TriggerPipelineReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-105">Initializes a new instance of the TriggerPipelineReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bb8c-106">取得またはパイプラインのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-106">Gets or sets pipeline parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.PipelineReference PipelineReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.PipelineReference PipelineReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference.PipelineReference" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineReference As PipelineReference" />
      <MemberSignature Language="F#" Value="member this.PipelineReference : Microsoft.Azure.Management.DataFactory.Models.PipelineReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference.PipelineReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bb8c-107">取得またはパイプラインの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-107">Gets or sets pipeline reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="triggerPipelineReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8bb8c-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8bb8c-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8bb8c-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>