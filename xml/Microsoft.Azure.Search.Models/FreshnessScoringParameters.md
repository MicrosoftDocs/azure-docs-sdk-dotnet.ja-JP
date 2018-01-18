<Type Name="FreshnessScoringParameters" FullName="Microsoft.Azure.Search.Models.FreshnessScoringParameters">
  <TypeSignature Language="C#" Value="public class FreshnessScoringParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FreshnessScoringParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.FreshnessScoringParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class FreshnessScoringParameters" />
  <TypeSignature Language="F#" Value="type FreshnessScoringParameters = class" />
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
            <span data-ttu-id="4877e-101">Freshness スコア付け関数のパラメーター値を提供します。</span><span class="sxs-lookup"><span data-stu-id="4877e-101">Provides parameter values to a freshness scoring function.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FreshnessScoringParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FreshnessScoringParameters.#ctor" />
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
            <span data-ttu-id="4877e-102">FreshnessScoringParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4877e-102">Initializes a new instance of the FreshnessScoringParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FreshnessScoringParameters (TimeSpan boostingDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan boostingDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FreshnessScoringParameters.#ctor(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (boostingDuration As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.FreshnessScoringParameters : TimeSpan -&gt; Microsoft.Azure.Search.Models.FreshnessScoringParameters" Usage="new Microsoft.Azure.Search.Models.FreshnessScoringParameters boostingDuration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="boostingDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="boostingDuration"><span data-ttu-id="4877e-103">特定のドキュメントに対しての期限を過ぎるとブースティングは停止します。</span><span class="sxs-lookup"><span data-stu-id="4877e-103">The expiration period after which boosting will stop for a particular document.</span></span></param>
        <summary>
            <span data-ttu-id="4877e-104">FreshnessScoringParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4877e-104">Initializes a new instance of the FreshnessScoringParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BoostingDuration">
      <MemberSignature Language="C#" Value="public TimeSpan BoostingDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BoostingDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FreshnessScoringParameters.BoostingDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property BoostingDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BoostingDuration : TimeSpan with get, set" Usage="Microsoft.Azure.Search.Models.FreshnessScoringParameters.BoostingDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="boostingDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4877e-105">取得または設定の特定のドキュメントの期限を過ぎるとブースティングは停止します。</span><span class="sxs-lookup"><span data-stu-id="4877e-105">Gets or sets the expiration period after which boosting will stop for a particular document.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FreshnessScoringParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="freshnessScoringParameters.Validate " />
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
            <span data-ttu-id="4877e-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4877e-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4877e-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4877e-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>