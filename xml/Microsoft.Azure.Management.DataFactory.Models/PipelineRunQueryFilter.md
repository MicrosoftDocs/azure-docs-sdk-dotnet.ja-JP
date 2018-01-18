<Type Name="PipelineRunQueryFilter" FullName="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter">
  <TypeSignature Language="C#" Value="public class PipelineRunQueryFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineRunQueryFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineRunQueryFilter" />
  <TypeSignature Language="F#" Value="type PipelineRunQueryFilter = class" />
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
            <span data-ttu-id="63566-101">パイプラインの実行を一覧表示するクエリのフィルター オプション。</span><span class="sxs-lookup"><span data-stu-id="63566-101">Query filter option for listing pipeline runs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.#ctor" />
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
            <span data-ttu-id="63566-102">PipelineRunQueryFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="63566-102">Initializes a new instance of the PipelineRunQueryFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryFilter (string operand, string operatorProperty, System.Collections.Generic.IList&lt;string&gt; values);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string operand, string operatorProperty, class System.Collections.Generic.IList`1&lt;string&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operand As String, operatorProperty As String, values As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter : string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter" Usage="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter (operand, operatorProperty, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operand" Type="System.String" />
        <Parameter Name="operatorProperty" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operand"><span data-ttu-id="63566-103">フィルターに使用するパラメーターの名前。</span><span class="sxs-lookup"><span data-stu-id="63566-103">Parameter name to be used for filter.</span></span>
            <span data-ttu-id="63566-104">使用可能な値が含まれます: 'PipelineName'、'Status'、'RunStart'、'RunEnd'</span><span class="sxs-lookup"><span data-stu-id="63566-104">Possible values include: 'PipelineName', 'Status', 'RunStart', 'RunEnd'</span></span></param>
        <param name="operatorProperty"><span data-ttu-id="63566-105">フィルターに使用する演算子です。</span><span class="sxs-lookup"><span data-stu-id="63566-105">Operator to be used for filter.</span></span>
            <span data-ttu-id="63566-106">使用可能な値が含まれます 'Equals'、'In'、'ない' ' NotEquals'、。</span><span class="sxs-lookup"><span data-stu-id="63566-106">Possible values include: 'Equals', 'NotEquals', 'In', 'NotIn'</span></span></param>
        <param name="values"><span data-ttu-id="63566-107">フィルター値の一覧です。</span><span class="sxs-lookup"><span data-stu-id="63566-107">List of filter values.</span></span></param>
        <summary>
            <span data-ttu-id="63566-108">PipelineRunQueryFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="63566-108">Initializes a new instance of the PipelineRunQueryFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operand">
      <MemberSignature Language="C#" Value="public string Operand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Operand" />
      <MemberSignature Language="VB.NET" Value="Public Property Operand As String" />
      <MemberSignature Language="F#" Value="member this.Operand : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Operand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63566-109">取得またはフィルターを使用するパラメーターの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="63566-109">Gets or sets parameter name to be used for filter.</span></span> <span data-ttu-id="63566-110">使用可能な値が含まれます: 'PipelineName'、'Status'、'RunStart'、'RunEnd'</span><span class="sxs-lookup"><span data-stu-id="63566-110">Possible values include: 'PipelineName', 'Status', 'RunStart', 'RunEnd'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorProperty">
      <MemberSignature Language="C#" Value="public string OperatorProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperatorProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.OperatorProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatorProperty As String" />
      <MemberSignature Language="F#" Value="member this.OperatorProperty : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.OperatorProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63566-111">取得またはフィルターを使用する演算子を設定します。</span><span class="sxs-lookup"><span data-stu-id="63566-111">Gets or sets operator to be used for filter.</span></span> <span data-ttu-id="63566-112">使用可能な値が含まれます 'Equals'、'In'、'ない' ' NotEquals'、。</span><span class="sxs-lookup"><span data-stu-id="63566-112">Possible values include: 'Equals', 'NotEquals', 'In', 'NotIn'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pipelineRunQueryFilter.Validate " />
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
            <span data-ttu-id="63566-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="63566-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63566-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63566-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63566-115">取得またはフィルター値の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="63566-115">Gets or sets list of filter values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>