<Type Name="FailoverSetEligibilityResult" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult">
  <TypeSignature Language="C#" Value="public class FailoverSetEligibilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverSetEligibilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverSetEligibilityResult" />
  <TypeSignature Language="F#" Value="type FailoverSetEligibilityResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7609a-101">フェールオーバーの対象となる結果は、フェールオーバーに設定します。</span><span class="sxs-lookup"><span data-stu-id="7609a-101">The eligibility result of failover set, for failover.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverSetEligibilityResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7609a-102">FailoverSetEligibilityResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7609a-102">Initializes a new instance of the FailoverSetEligibilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverSetEligibilityResult (Nullable&lt;bool&gt; isEligibleForFailover = null, string errorMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; isEligibleForFailover, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult.#ctor(System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional isEligibleForFailover As Nullable(Of Boolean) = null, Optional errorMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult : Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult (isEligibleForFailover, errorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isEligibleForFailover" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="errorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isEligibleForFailover"><span data-ttu-id="7609a-103">このフェールオーバー セットがフェールオーバーの対象であるか場合、を表します。</span><span class="sxs-lookup"><span data-stu-id="7609a-103">Represents if this failover set is eligible for failover or not.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="7609a-104">フェールオーバー セットは、フェールオーバーの対象がない場合のエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="7609a-104">The error message, if the failover set is not eligible for failover.</span></span></param>
        <summary>
            <span data-ttu-id="7609a-105">FailoverSetEligibilityResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7609a-105">Initializes a new instance of the FailoverSetEligibilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7609a-106">取得またはフェールオーバー セットは、フェールオーバーの対象がない場合に、エラー メッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="7609a-106">Gets or sets the error message, if the failover set is not eligible for failover.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEligibleForFailover">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsEligibleForFailover { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsEligibleForFailover" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult.IsEligibleForFailover" />
      <MemberSignature Language="VB.NET" Value="Public Property IsEligibleForFailover As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsEligibleForFailover : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult.IsEligibleForFailover" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isEligibleForFailover")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7609a-107">取得または設定を表す場合このフェールオーバー セットがフェールオーバーの対象であるか。</span><span class="sxs-lookup"><span data-stu-id="7609a-107">Gets or sets represents if this failover set is eligible for failover or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>