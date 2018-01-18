<Type Name="TransformationsCreateOrReplaceHeaders" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders">
  <TypeSignature Language="C#" Value="public class TransformationsCreateOrReplaceHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransformationsCreateOrReplaceHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class TransformationsCreateOrReplaceHeaders" />
  <TypeSignature Language="F#" Value="type TransformationsCreateOrReplaceHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04821-101">CreateOrReplace 操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="04821-101">Defines headers for CreateOrReplace operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransformationsCreateOrReplaceHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04821-102">TransformationsCreateOrReplaceHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="04821-102">Initializes a new instance of the TransformationsCreateOrReplaceHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransformationsCreateOrReplaceHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders : string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="04821-103">変換の現在のエンティティ タグ。</span><span class="sxs-lookup"><span data-stu-id="04821-103">The current entity tag for the transformation.</span></span>
            <span data-ttu-id="04821-104">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="04821-104">This is an opaque string.</span></span> <span data-ttu-id="04821-105">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="04821-105">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="04821-106">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="04821-106">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <summary>
            <span data-ttu-id="04821-107">TransformationsCreateOrReplaceHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="04821-107">Initializes a new instance of the TransformationsCreateOrReplaceHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04821-108">取得または変換の現在のエンティティ タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="04821-108">Gets or sets the current entity tag for the transformation.</span></span> <span data-ttu-id="04821-109">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="04821-109">This is an opaque string.</span></span> <span data-ttu-id="04821-110">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="04821-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="04821-111">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="04821-111">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>