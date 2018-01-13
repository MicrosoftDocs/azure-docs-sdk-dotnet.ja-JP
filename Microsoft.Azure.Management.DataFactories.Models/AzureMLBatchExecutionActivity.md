<Type Name="AzureMLBatchExecutionActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity">
  <TypeSignature Language="C#" Value="public class AzureMLBatchExecutionActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLBatchExecutionActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLBatchExecutionActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLBatchExecutionActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureMLBatchExecution")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e41a5-101">Azure ML バッチ実行サービス アクティビティ。</span><span class="sxs-lookup"><span data-stu-id="e41a5-101">Azure ML Batch Execution Service activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchExecutionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; GlobalParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GlobalParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalParameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GlobalParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e41a5-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e41a5-102">Optional.</span></span> <span data-ttu-id="e41a5-103">Azure ML バッチ実行サービス エンドポイントに渡されるキーの値のペア。</span><span class="sxs-lookup"><span data-stu-id="e41a5-103">Key,Value pairs to be passed to the Azure ML Batch Execution Service Endpoint.</span></span> <span data-ttu-id="e41a5-104">キーは、公開済みの Azure ML Web サービスで定義されている、Web サービスのパラメーターの名前と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e41a5-104">Keys must match the names of web service parameters defined in the published Azure ML web service.</span></span> <span data-ttu-id="e41a5-105">値には、各スライスの実行時 (を参照してください http://go.microsoft.com/fwlink/?LinkId=823697) に解決する Azure Data Factory 関数を含めることがあります。</span><span class="sxs-lookup"><span data-stu-id="e41a5-105">Values may include Azure Data Factory functions to be resolved at each slice execution time (See http://go.microsoft.com/fwlink/?LinkId=823697).</span></span> <span data-ttu-id="e41a5-106">Azure ML バッチ実行要求の globalparameters にあるプロパティに値が渡されます。</span><span class="sxs-lookup"><span data-stu-id="e41a5-106">Values will be passed in the GlobalParameters property of the Azure ML batch execution request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInput">
      <MemberSignature Language="C#" Value="public string WebServiceInput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WebServiceInput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInput As String" />
      <MemberSignature Language="F#" Value="member this.WebServiceInput : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e41a5-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e41a5-107">Optional.</span></span> <span data-ttu-id="e41a5-108">バッチ実行への入力を提供するデータ ファクトリのデータセットの名前です。</span><span class="sxs-lookup"><span data-stu-id="e41a5-108">Name of Data Factory dataset giving the input to the batch execution.</span></span> <span data-ttu-id="e41a5-109">この情報は、Azure ML バッチ実行要求の WebServiceInput プロパティに渡されます。</span><span class="sxs-lookup"><span data-stu-id="e41a5-109">This information will be passed in the WebServiceInput property of the Azure ML batch execution request.</span></span> <span data-ttu-id="e41a5-110">WebServiceInput は、WebServiceInputs で同時には使用できません。</span><span class="sxs-lookup"><span data-stu-id="e41a5-110">WebServiceInput cannot be used simultaneously with WebServiceInputs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceInputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceInputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceInputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e41a5-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e41a5-111">Optional.</span></span> <span data-ttu-id="e41a5-112">マッピングに Data Factory のデータセットの名前の Azure ML web サービスの入力の名前、キーの値のペア。</span><span class="sxs-lookup"><span data-stu-id="e41a5-112">Key, Value pairs mapping the names of Azure ML web service inputs to names of Data Factory datasets.</span></span>
            <span data-ttu-id="e41a5-113">バッチ実行の入力は、これらのデータセットに格納されます。</span><span class="sxs-lookup"><span data-stu-id="e41a5-113">The batch execution input is stored in these datasets.</span></span>
            <span data-ttu-id="e41a5-114">この情報は、Azure ML バッチ実行要求の WebServiceInputs プロパティに渡されます。</span><span class="sxs-lookup"><span data-stu-id="e41a5-114">This information will be passed in the WebServiceInputs property of the Azure ML batch execution request.</span></span>
            <span data-ttu-id="e41a5-115">アクティビティの入力では、マップされたデータセットを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="e41a5-115">Mapped datasets must be included in the Activity's inputs.</span></span> <span data-ttu-id="e41a5-116">WebServiceInputs は、WebServiceInput で同時には使用できません。</span><span class="sxs-lookup"><span data-stu-id="e41a5-116">WebServiceInputs cannot be used simultaneously with WebServiceInput.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceOutputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceOutputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceOutputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceOutputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e41a5-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e41a5-117">Optional.</span></span> <span data-ttu-id="e41a5-118">キー、値のペアが Azure ML web サービスの出力の名前をデータ ファクトリのデータセットの名前にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="e41a5-118">Key, Value pairs mapping the names of Azure ML web service outputs to names of Data Factory datasets.</span></span>
            <span data-ttu-id="e41a5-119">バッチ実行の出力は、これらのデータセットに書き込まれます。</span><span class="sxs-lookup"><span data-stu-id="e41a5-119">The batch execution output is written to these datasets.</span></span>
            <span data-ttu-id="e41a5-120">この情報は、Azure ML バッチ実行要求の webserviceoutputs にあるプロパティに渡されます。</span><span class="sxs-lookup"><span data-stu-id="e41a5-120">This information will be passed in the WebServiceOutputs property of the Azure ML batch execution request.</span></span>
            <span data-ttu-id="e41a5-121">アクティビティの出力では、マップされたデータセットを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="e41a5-121">Mapped datasets must be included in the Activity's outputs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>