<Type Name="AzureMachineLearningWebServiceFunctionBinding" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding">
  <TypeSignature Language="C#" Value="public class AzureMachineLearningWebServiceFunctionBinding : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMachineLearningWebServiceFunctionBinding extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMachineLearningWebServiceFunctionBinding&#xA;Inherits FunctionBinding" />
  <TypeSignature Language="F#" Value="type AzureMachineLearningWebServiceFunctionBinding = class&#xA;    inherit FunctionBinding" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.MachineLearning/WebService")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1e563-101">Azure Machine Learning web サービスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="1e563-101">The binding to an Azure Machine Learning web service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceFunctionBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e563-102">AzureMachineLearningWebServiceFunctionBinding クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e563-102">Initializes a new instance of the AzureMachineLearningWebServiceFunctionBinding class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceFunctionBinding (string endpoint = null, string apiKey = null, Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs inputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; outputs = null, Nullable&lt;int&gt; batchSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string apiKey, class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs inputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; outputs, valuetype System.Nullable`1&lt;int32&gt; batchSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.#ctor(System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs,System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional endpoint As String = null, Optional apiKey As String = null, Optional inputs As AzureMachineLearningWebServiceInputs = null, Optional outputs As IList(Of AzureMachineLearningWebServiceOutputColumn) = null, Optional batchSize As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding : string * string * Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding (endpoint, apiKey, inputs, outputs, batchSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="apiKey" Type="System.String" />
        <Parameter Name="inputs" Type="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs" />
        <Parameter Name="outputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt;" />
        <Parameter Name="batchSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="1e563-103">要求-応答は、Azure Machine Learning web サービスのエンドポイントを実行します。</span><span class="sxs-lookup"><span data-stu-id="1e563-103">The Request-Response execute endpoint of the Azure Machine Learning web service.</span></span> <span data-ttu-id="1e563-104">ここでは詳細に調べる: https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-consume-web-services#request-response-service-rrs</span><span class="sxs-lookup"><span data-stu-id="1e563-104">Find out more here: https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-consume-web-services#request-response-service-rrs</span></span></param>
        <param name="apiKey"><span data-ttu-id="1e563-105">API キーは、要求-応答エンドポイントとの認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="1e563-105">The API key used to authenticate with Request-Response endpoint.</span></span></param>
        <param name="inputs"><span data-ttu-id="1e563-106">Azure Machine Learning web サービスのエンドポイントを入力します。</span><span class="sxs-lookup"><span data-stu-id="1e563-106">The inputs for the Azure Machine Learning web service endpoint.</span></span></param>
        <param name="outputs"><span data-ttu-id="1e563-107">Azure Machine Learning web サービス エンドポイントの実行からの出力の一覧。</span><span class="sxs-lookup"><span data-stu-id="1e563-107">A list of outputs from the Azure Machine Learning web service endpoint execution.</span></span></param>
        <param name="batchSize"><span data-ttu-id="1e563-108">1 ~ 10000 行の最大数を記述するすべての Azure ML RR の数値は、要求を実行します。</span><span class="sxs-lookup"><span data-stu-id="1e563-108">Number between 1 and 10000 describing maximum number of rows for every Azure ML RRS execute request.</span></span>
            <span data-ttu-id="1e563-109">既定値は 1000 です。</span><span class="sxs-lookup"><span data-stu-id="1e563-109">Default is 1000.</span></span></param>
        <summary>
            <span data-ttu-id="1e563-110">AzureMachineLearningWebServiceFunctionBinding クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e563-110">Initializes a new instance of the AzureMachineLearningWebServiceFunctionBinding class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public string ApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiKey As String" />
      <MemberSignature Language="F#" Value="member this.ApiKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apiKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e563-111">取得または要求-応答エンドポイントでの認証に使用する API キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="1e563-111">Gets or sets the API key used to authenticate with Request-Response endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.BatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BatchSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.BatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.batchSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e563-112">取得または 1 ~ 10000 行の最大数を記述するすべての Azure ML RR 要求の実行の数値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1e563-112">Gets or sets number between 1 and 10000 describing maximum number of rows for every Azure ML RRS execute request.</span></span> <span data-ttu-id="1e563-113">既定値は 1000 です。</span><span class="sxs-lookup"><span data-stu-id="1e563-113">Default is 1000.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e563-114">要求-応答を取得または設定は、Azure Machine Learning web サービスのエンドポイントを実行します。</span><span class="sxs-lookup"><span data-stu-id="1e563-114">Gets or sets the Request-Response execute endpoint of the Azure Machine Learning web service.</span></span> <span data-ttu-id="1e563-115">ここでは詳細に調べる: https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-consume-web-services#request-response-service-rrs</span><span class="sxs-lookup"><span data-stu-id="1e563-115">Find out more here: https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-consume-web-services#request-response-service-rrs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As AzureMachineLearningWebServiceInputs" />
      <MemberSignature Language="F#" Value="member this.Inputs : Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e563-116">取得または設定、Azure Machine Learning web サービス エンドポイントを入力します。</span><span class="sxs-lookup"><span data-stu-id="1e563-116">Gets or sets the inputs for the Azure Machine Learning web service endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of AzureMachineLearningWebServiceOutputColumn)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e563-117">取得または Azure Machine Learning web サービス エンドポイントの実行による出力の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="1e563-117">Gets or sets a list of outputs from the Azure Machine Learning web service endpoint execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>