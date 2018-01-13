<Type Name="ScalarFunctionProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties">
  <TypeSignature Language="C#" Value="public class ScalarFunctionProperties : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScalarFunctionProperties extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ScalarFunctionProperties&#xA;Inherits FunctionProperties" />
  <TypeSignature Language="F#" Value="type ScalarFunctionProperties = class&#xA;    inherit FunctionProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Scalar")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c4189-101">スカラー関数に関連付けられているプロパティです。</span><span class="sxs-lookup"><span data-stu-id="c4189-101">The properties that are associated with a scalar function.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScalarFunctionProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4189-102">ScalarFunctionProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c4189-102">Initializes a new instance of the ScalarFunctionProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScalarFunctionProperties (string etag = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt; inputs = null, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput output = null, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding binding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string etag, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt; inputs, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput output, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput},Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional etag As String = null, Optional inputs As IList(Of FunctionInput) = null, Optional output As FunctionOutput = null, Optional binding As FunctionBinding = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt; * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties (etag, inputs, output, binding)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="inputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt;" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput" />
        <Parameter Name="binding" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
      </Parameters>
      <Docs>
        <param name="etag"><span data-ttu-id="c4189-103">関数の現在のエンティティ タグ。</span><span class="sxs-lookup"><span data-stu-id="c4189-103">The current entity tag for the function.</span></span> <span data-ttu-id="c4189-104">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="c4189-104">This is an opaque string.</span></span> <span data-ttu-id="c4189-105">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="c4189-105">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="c4189-106">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="c4189-106">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <param name="inputs"><span data-ttu-id="c4189-107">関数のパラメーターを記述する入力の一覧。</span><span class="sxs-lookup"><span data-stu-id="c4189-107">A list of inputs describing the parameters of the function.</span></span></param>
        <param name="output"><span data-ttu-id="c4189-108">関数の出力です。</span><span class="sxs-lookup"><span data-stu-id="c4189-108">The output of the function.</span></span></param>
        <param name="binding"><span data-ttu-id="c4189-109">関数の物理的なバインディング。</span><span class="sxs-lookup"><span data-stu-id="c4189-109">The physical binding of the function.</span></span> <span data-ttu-id="c4189-110">たとえば、Azure Machine Learning web サービスの場合は、エンドポイントを説明します。</span><span class="sxs-lookup"><span data-stu-id="c4189-110">For example, in the Azure Machine Learning web service’s case, this describes the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="c4189-111">ScalarFunctionProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c4189-111">Initializes a new instance of the ScalarFunctionProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Binding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding Binding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding Binding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.Binding" />
      <MemberSignature Language="VB.NET" Value="Public Property Binding As FunctionBinding" />
      <MemberSignature Language="F#" Value="member this.Binding : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.Binding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.binding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4189-112">取得または関数の物理的なバインドを設定します。</span><span class="sxs-lookup"><span data-stu-id="c4189-112">Gets or sets the physical binding of the function.</span></span> <span data-ttu-id="c4189-113">たとえば、Azure Machine Learning web サービスの場合は、エンドポイントを説明します。</span><span class="sxs-lookup"><span data-stu-id="c4189-113">For example, in the Azure Machine Learning web service’s case, this describes the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt; Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt; Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As IList(Of FunctionInput)" />
      <MemberSignature Language="F#" Value="member this.Inputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.Inputs" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.FunctionInput&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4189-114">取得または関数のパラメーターを記述する入力の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c4189-114">Gets or sets a list of inputs describing the parameters of the function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Output">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput Output { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput Output" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.Output" />
      <MemberSignature Language="VB.NET" Value="Public Property Output As FunctionOutput" />
      <MemberSignature Language="F#" Value="member this.Output : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ScalarFunctionProperties.Output" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.output")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionOutput</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4189-115">取得または関数の出力を設定します。</span><span class="sxs-lookup"><span data-stu-id="c4189-115">Gets or sets the output of the function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>