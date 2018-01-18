<Type Name="JavaScriptFunctionRetrieveDefaultDefinitionParameters" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters">
  <TypeSignature Language="C#" Value="public class JavaScriptFunctionRetrieveDefaultDefinitionParameters : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JavaScriptFunctionRetrieveDefaultDefinitionParameters extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class JavaScriptFunctionRetrieveDefaultDefinitionParameters&#xA;Inherits FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="F#" Value="type JavaScriptFunctionRetrieveDefaultDefinitionParameters = class&#xA;    inherit FunctionRetrieveDefaultDefinitionParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.StreamAnalytics/JavascriptUdf")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="51075-101">JavaScript 関数の既定の関数定義の取得に必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="51075-101">The parameters needed to retrieve the default function definition for a JavaScript function.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionRetrieveDefaultDefinitionParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="51075-102">JavaScriptFunctionRetrieveDefaultDefinitionParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="51075-102">Initializes a new instance of the JavaScriptFunctionRetrieveDefaultDefinitionParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionRetrieveDefaultDefinitionParameters (string script = null, Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; udfType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; udfType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.StreamAnalytics.Models.UdfType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional script As String = null, Optional udfType As Nullable(Of UdfType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters : string * Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters (script, udfType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
        <Parameter Name="udfType" Type="System.Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt;" />
      </Parameters>
      <Docs>
        <param name="script"><span data-ttu-id="51075-103">1 つの関数定義を含む JavaScript コードです。</span><span class="sxs-lookup"><span data-stu-id="51075-103">The JavaScript code containing a single function definition.</span></span> <span data-ttu-id="51075-104">例: ' function (x, y) {リターン文字 x と y;}'。</span><span class="sxs-lookup"><span data-stu-id="51075-104">For example: 'function (x, y) { return x + y; }'.</span></span></param>
        <param name="udfType"><span data-ttu-id="51075-105">関数の型。</span><span class="sxs-lookup"><span data-stu-id="51075-105">The function type.</span></span> <span data-ttu-id="51075-106">使用可能な値が含まれます: 'スカラー'</span><span class="sxs-lookup"><span data-stu-id="51075-106">Possible values include: 'Scalar'</span></span></param>
        <summary>
            <span data-ttu-id="51075-107">JavaScriptFunctionRetrieveDefaultDefinitionParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="51075-107">Initializes a new instance of the JavaScriptFunctionRetrieveDefaultDefinitionParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bindingRetrievalProperties.script")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="51075-108">取得または 1 つの関数定義を含む JavaScript コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="51075-108">Gets or sets the JavaScript code containing a single function definition.</span></span> <span data-ttu-id="51075-109">例: ' function (x, y) {リターン文字 x と y;}'。</span><span class="sxs-lookup"><span data-stu-id="51075-109">For example: 'function (x, y) { return x + y; }'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UdfType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; UdfType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; UdfType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.UdfType" />
      <MemberSignature Language="VB.NET" Value="Public Property UdfType As Nullable(Of UdfType)" />
      <MemberSignature Language="F#" Value="member this.UdfType : Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.UdfType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bindingRetrievalProperties.udfType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="51075-110">取得または関数の型を設定します。</span><span class="sxs-lookup"><span data-stu-id="51075-110">Gets or sets the function type.</span></span> <span data-ttu-id="51075-111">使用可能な値が含まれます: 'スカラー'</span><span class="sxs-lookup"><span data-stu-id="51075-111">Possible values include: 'Scalar'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>