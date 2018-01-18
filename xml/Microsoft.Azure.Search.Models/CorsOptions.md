<Type Name="CorsOptions" FullName="Microsoft.Azure.Search.Models.CorsOptions">
  <TypeSignature Language="C#" Value="public class CorsOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CorsOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CorsOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class CorsOptions" />
  <TypeSignature Language="F#" Value="type CorsOptions = class" />
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
            <span data-ttu-id="a8d04-101">インデックスのクロス オリジン リソース共有 (CORS) を制御するオプションを定義します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-101">Defines options to control Cross-Origin Resource Sharing (CORS) for an index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorsOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CorsOptions.#ctor" />
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
            <span data-ttu-id="a8d04-102">CorsOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-102">Initializes a new instance of the CorsOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorsOptions (System.Collections.Generic.IList&lt;string&gt; allowedOrigins, Nullable&lt;long&gt; maxAgeInSeconds = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; allowedOrigins, valuetype System.Nullable`1&lt;int64&gt; maxAgeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CorsOptions.#ctor(System.Collections.Generic.IList{System.String},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (allowedOrigins As IList(Of String), Optional maxAgeInSeconds As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CorsOptions : System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Search.Models.CorsOptions" Usage="new Microsoft.Azure.Search.Models.CorsOptions (allowedOrigins, maxAgeInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="allowedOrigins" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="maxAgeInSeconds" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="allowedOrigins"><span data-ttu-id="a8d04-103">どの JavaScript からコードがアクセスを許可する、インデックスにオリジンのリスト。</span><span class="sxs-lookup"><span data-stu-id="a8d04-103">The list of origins from which JavaScript code will be granted access to your index.</span></span> <span data-ttu-id="a8d04-104">://{プロトコル} のフォームのホストの一覧を含めることができる {完全修飾ドメイン-名} [: {ポート番号}]、または 1 つの ' \*' (推奨しません) すべてのオリジンを許可します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-104">Can contain a list of hosts of the form {protocol}://{fully-qualified-domain-name}[:{port#}], or a single '\*' to allow all origins (not recommended).</span></span></param>
        <param name="maxAgeInSeconds"><span data-ttu-id="a8d04-105">ブラウザーが CORS プレフライト応答をキャッシュする期間です。</span><span class="sxs-lookup"><span data-stu-id="a8d04-105">The duration for which browsers should cache CORS preflight responses.</span></span> <span data-ttu-id="a8d04-106">既定値は 5 分後です。</span><span class="sxs-lookup"><span data-stu-id="a8d04-106">Defaults to 5 mintues.</span></span></param>
        <summary>
            <span data-ttu-id="a8d04-107">CorsOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-107">Initializes a new instance of the CorsOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedOrigins">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedOrigins { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedOrigins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CorsOptions.AllowedOrigins" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedOrigins As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedOrigins : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CorsOptions.AllowedOrigins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowedOrigins")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d04-108">取得または元の JavaScript コードがアクセスを許可する、インデックスにオリジンのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-108">Gets or sets the list of origins from which JavaScript code will be granted access to your index.</span></span> <span data-ttu-id="a8d04-109">://{プロトコル} のフォームのホストの一覧を含めることができる {完全修飾ドメイン-名} [: {ポート番号}]、または 1 つの ' \*' (推奨しません) すべてのオリジンを許可します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-109">Can contain a list of hosts of the form {protocol}://{fully-qualified-domain-name}[:{port#}], or a single '\*' to allow all origins (not recommended).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAgeInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxAgeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxAgeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CorsOptions.MaxAgeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAgeInSeconds As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxAgeInSeconds : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CorsOptions.MaxAgeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxAgeInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8d04-110">取得またはブラウザーが CORS プレフライト応答をキャッシュする期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-110">Gets or sets the duration for which browsers should cache CORS preflight responses.</span></span> <span data-ttu-id="a8d04-111">既定値は 5 分後です。</span><span class="sxs-lookup"><span data-stu-id="a8d04-111">Defaults to 5 mintues.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CorsOptions.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="corsOptions.Validate " />
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
            <span data-ttu-id="a8d04-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a8d04-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a8d04-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a8d04-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>