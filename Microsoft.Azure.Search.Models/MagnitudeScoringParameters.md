<Type Name="MagnitudeScoringParameters" FullName="Microsoft.Azure.Search.Models.MagnitudeScoringParameters">
  <TypeSignature Language="C#" Value="public class MagnitudeScoringParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MagnitudeScoringParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MagnitudeScoringParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class MagnitudeScoringParameters" />
  <TypeSignature Language="F#" Value="type MagnitudeScoringParameters = class" />
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
            Magnitude スコア付け関数のパラメーター値を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MagnitudeScoringParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MagnitudeScoringParameters.#ctor" />
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
            MagnitudeScoringParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MagnitudeScoringParameters (double boostingRangeStart, double boostingRangeEnd, Nullable&lt;bool&gt; shouldBoostBeyondRangeByConstant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 boostingRangeStart, float64 boostingRangeEnd, valuetype System.Nullable`1&lt;bool&gt; shouldBoostBeyondRangeByConstant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MagnitudeScoringParameters.#ctor(System.Double,System.Double,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (boostingRangeStart As Double, boostingRangeEnd As Double, Optional shouldBoostBeyondRangeByConstant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MagnitudeScoringParameters : double * double * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.MagnitudeScoringParameters" Usage="new Microsoft.Azure.Search.Models.MagnitudeScoringParameters (boostingRangeStart, boostingRangeEnd, shouldBoostBeyondRangeByConstant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="boostingRangeStart" Type="System.Double" />
        <Parameter Name="boostingRangeEnd" Type="System.Double" />
        <Parameter Name="shouldBoostBeyondRangeByConstant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="boostingRangeStart">フィールド値を指定では、開始を向上します。</param>
        <param name="boostingRangeEnd">フィールド値を指定では、終了を向上します。</param>
        <param name="shouldBoostBeyondRangeByConstant">一定のブースト; 範囲の終了値を超えるフィールドの値を適用するかどうかを示す値既定値は false です。</param>
        <summary>
            MagnitudeScoringParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BoostingRangeEnd">
      <MemberSignature Language="C#" Value="public double BoostingRangeEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 BoostingRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MagnitudeScoringParameters.BoostingRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property BoostingRangeEnd As Double" />
      <MemberSignature Language="F#" Value="member this.BoostingRangeEnd : double with get, set" Usage="Microsoft.Azure.Search.Models.MagnitudeScoringParameters.BoostingRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="boostingRangeEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはブースティング終了でフィールド値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BoostingRangeStart">
      <MemberSignature Language="C#" Value="public double BoostingRangeStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 BoostingRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MagnitudeScoringParameters.BoostingRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public Property BoostingRangeStart As Double" />
      <MemberSignature Language="F#" Value="member this.BoostingRangeStart : double with get, set" Usage="Microsoft.Azure.Search.Models.MagnitudeScoringParameters.BoostingRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="boostingRangeStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはブーストが開始位置フィールド値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldBoostBeyondRangeByConstant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ShouldBoostBeyondRangeByConstant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ShouldBoostBeyondRangeByConstant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MagnitudeScoringParameters.ShouldBoostBeyondRangeByConstant" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldBoostBeyondRangeByConstant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ShouldBoostBeyondRangeByConstant : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MagnitudeScoringParameters.ShouldBoostBeyondRangeByConstant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constantBoostBeyondRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または一定のブースト; 範囲の終了値を超えるフィールドの値を適用するかどうかを示す値を設定既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MagnitudeScoringParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="magnitudeScoringParameters.Validate " />
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