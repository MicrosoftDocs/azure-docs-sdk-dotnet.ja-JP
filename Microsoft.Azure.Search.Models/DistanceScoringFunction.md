<Type Name="DistanceScoringFunction" FullName="Microsoft.Azure.Search.Models.DistanceScoringFunction">
  <TypeSignature Language="C#" Value="public class DistanceScoringFunction : Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DistanceScoringFunction extends Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DistanceScoringFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class DistanceScoringFunction&#xA;Inherits ScoringFunction" />
  <TypeSignature Language="F#" Value="type DistanceScoringFunction = class&#xA;    inherit ScoringFunction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ScoringFunction</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("distance")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            地理的位置からの距離に基づいてスコアをブーストする関数を定義します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistanceScoringFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.#ctor" />
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
            DistanceScoringFunction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistanceScoringFunction (string fieldName, double boost, Microsoft.Azure.Search.Models.DistanceScoringParameters parameters, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, class Microsoft.Azure.Search.Models.DistanceScoringParameters parameters, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.#ctor(System.String,System.Double,Microsoft.Azure.Search.Models.DistanceScoringParameters,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, parameters As DistanceScoringParameters, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DistanceScoringFunction : string * double * Microsoft.Azure.Search.Models.DistanceScoringParameters * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.DistanceScoringFunction" Usage="new Microsoft.Azure.Search.Models.DistanceScoringFunction (fieldName, boost, parameters, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.DistanceScoringParameters" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName">スコア付け関数への入力として使用されるフィールドの名前。</param>
        <param name="boost">生のスコアの乗数。 解除する必要が正の数値 1.0 に等しくします。</param>
        <param name="parameters">距離のスコア付け関数のパラメーター値。</param>
        <param name="interpolation">どのブースティングはするで補間ドキュメントのスコアを示す値既定値は「線形」です。 使用可能な値が含まれます: 'linear'、'定数'、'二次'、'対数'</param>
        <summary>
            DistanceScoringFunction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistanceScoringFunction (string fieldName, double boost, string referencePointParameter, double boostingDistance, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, string referencePointParameter, float64 boostingDistance, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.#ctor(System.String,System.Double,System.String,System.Double,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, referencePointParameter As String, boostingDistance As Double, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DistanceScoringFunction : string * double * string * double * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.DistanceScoringFunction" Usage="new Microsoft.Azure.Search.Models.DistanceScoringFunction (fieldName, boost, referencePointParameter, boostingDistance, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="referencePointParameter" Type="System.String" />
        <Parameter Name="boostingDistance" Type="System.Double" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName">To be added.</param>
        <param name="boost">To be added.</param>
        <param name="referencePointParameter">To be added.</param>
        <param name="boostingDistance">To be added.</param>
        <param name="interpolation">To be added.</param>
        <summary>
            DistanceScoringFunction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DistanceScoringParameters Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DistanceScoringParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DistanceScoringFunction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As DistanceScoringParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Search.Models.DistanceScoringParameters with get, set" Usage="Microsoft.Azure.Search.Models.DistanceScoringFunction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="distance")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DistanceScoringParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または距離をスコア付け関数のパラメーターの値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="distanceScoringFunction.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>