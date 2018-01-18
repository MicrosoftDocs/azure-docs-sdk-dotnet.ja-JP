<Type Name="ScoringFunction" FullName="Microsoft.Azure.Search.Models.ScoringFunction">
  <TypeSignature Language="C#" Value="public class ScoringFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScoringFunction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class ScoringFunction" />
  <TypeSignature Language="F#" Value="type ScoringFunction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="34aad-101">順位付け時にドキュメントのスコアを変更できる機能の抽象基本クラスです。</span><span class="sxs-lookup"><span data-stu-id="34aad-101">Abstract base class for functions that can modify document scores during ranking.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringFunction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="34aad-102">ScoringFunction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34aad-102">Initializes a new instance of the ScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringFunction (string fieldName, double boost, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringFunction.#ctor(System.String,System.Double,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ScoringFunction : string * double * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.ScoringFunction" Usage="new Microsoft.Azure.Search.Models.ScoringFunction (fieldName, boost, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName"><span data-ttu-id="34aad-103">スコア付け関数への入力として使用されるフィールドの名前。</span><span class="sxs-lookup"><span data-stu-id="34aad-103">The name of the field used as input to the scoring function.</span></span></param>
        <param name="boost"><span data-ttu-id="34aad-104">生のスコアの乗数。</span><span class="sxs-lookup"><span data-stu-id="34aad-104">A multiplier for the raw score.</span></span> <span data-ttu-id="34aad-105">解除する必要が正の数値 1.0 に等しくします。</span><span class="sxs-lookup"><span data-stu-id="34aad-105">Must be a positive number not equal to 1.0.</span></span></param>
        <param name="interpolation"><span data-ttu-id="34aad-106">どのブースティングはするで補間ドキュメントのスコアを示す値既定値は「線形」です。</span><span class="sxs-lookup"><span data-stu-id="34aad-106">A value indicating how boosting will be interpolated across document scores; defaults to "Linear".</span></span> <span data-ttu-id="34aad-107">使用可能な値が含まれます: 'linear'、'定数'、'二次'、'対数'</span><span class="sxs-lookup"><span data-stu-id="34aad-107">Possible values include: 'linear', 'constant', 'quadratic', 'logarithmic'</span></span></param>
        <summary>
            <span data-ttu-id="34aad-108">ScoringFunction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34aad-108">Initializes a new instance of the ScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Boost">
      <MemberSignature Language="C#" Value="public double Boost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Boost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringFunction.Boost" />
      <MemberSignature Language="VB.NET" Value="Public Property Boost As Double" />
      <MemberSignature Language="F#" Value="member this.Boost : double with get, set" Usage="Microsoft.Azure.Search.Models.ScoringFunction.Boost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="boost")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34aad-109">取得または生のスコアの乗数を設定します。</span><span class="sxs-lookup"><span data-stu-id="34aad-109">Gets or sets a multiplier for the raw score.</span></span> <span data-ttu-id="34aad-110">解除する必要が正の数値 1.0 に等しくします。</span><span class="sxs-lookup"><span data-stu-id="34aad-110">Must be a positive number not equal to 1.0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FieldName">
      <MemberSignature Language="C#" Value="public string FieldName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringFunction.FieldName" />
      <MemberSignature Language="VB.NET" Value="Public Property FieldName As String" />
      <MemberSignature Language="F#" Value="member this.FieldName : string with get, set" Usage="Microsoft.Azure.Search.Models.ScoringFunction.FieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fieldName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34aad-111">取得またはスコア付け関数への入力として使用されるフィールドの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="34aad-111">Gets or sets the name of the field used as input to the scoring function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interpolation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; Interpolation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; Interpolation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringFunction.Interpolation" />
      <MemberSignature Language="VB.NET" Value="Public Property Interpolation As Nullable(Of ScoringFunctionInterpolation)" />
      <MemberSignature Language="F#" Value="member this.Interpolation : Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ScoringFunction.Interpolation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="interpolation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34aad-112">取得または方法ブースティングはあるで補間ドキュメントのスコアを示す値を設定既定値は「線形」です。</span><span class="sxs-lookup"><span data-stu-id="34aad-112">Gets or sets a value indicating how boosting will be interpolated across document scores; defaults to "Linear".</span></span> <span data-ttu-id="34aad-113">使用可能な値が含まれます: 'linear'、'定数'、'二次'、'対数'</span><span class="sxs-lookup"><span data-stu-id="34aad-113">Possible values include: 'linear', 'constant', 'quadratic', 'logarithmic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scoringFunction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="34aad-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="34aad-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="34aad-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="34aad-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>