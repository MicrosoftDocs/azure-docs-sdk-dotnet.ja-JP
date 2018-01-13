<Type Name="JavaScriptFunctionBinding" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding">
  <TypeSignature Language="C#" Value="public class JavaScriptFunctionBinding : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JavaScriptFunctionBinding extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class JavaScriptFunctionBinding&#xA;Inherits FunctionBinding" />
  <TypeSignature Language="F#" Value="type JavaScriptFunctionBinding = class&#xA;    inherit FunctionBinding" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.StreamAnalytics/JavascriptUdf")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e4583-101">JavaScript 関数をバインドします。</span><span class="sxs-lookup"><span data-stu-id="e4583-101">The binding to a JavaScript function.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e4583-102">JavaScriptFunctionBinding クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e4583-102">Initializes a new instance of the JavaScriptFunctionBinding class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionBinding (string script = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional script As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding : string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding script" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="script"><span data-ttu-id="e4583-103">1 つの関数定義を含む JavaScript コードです。</span><span class="sxs-lookup"><span data-stu-id="e4583-103">The JavaScript code containing a single function definition.</span></span> <span data-ttu-id="e4583-104">例: ' function (x, y) {リターン文字 x と y;}'</span><span class="sxs-lookup"><span data-stu-id="e4583-104">For example: 'function (x, y) { return x + y; }'</span></span></param>
        <summary>
            <span data-ttu-id="e4583-105">JavaScriptFunctionBinding クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e4583-105">Initializes a new instance of the JavaScriptFunctionBinding class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.script")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4583-106">取得または 1 つの関数定義を含む JavaScript コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="e4583-106">Gets or sets the JavaScript code containing a single function definition.</span></span> <span data-ttu-id="e4583-107">例: ' function (x, y) {リターン文字 x と y;}'</span><span class="sxs-lookup"><span data-stu-id="e4583-107">For example: 'function (x, y) { return x + y; }'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>