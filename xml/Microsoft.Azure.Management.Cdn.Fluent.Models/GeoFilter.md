<Type Name="GeoFilter" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter">
  <TypeSignature Language="C#" Value="public class GeoFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GeoFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class GeoFilter" />
  <TypeSignature Language="F#" Value="type GeoFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29d7d-101">CDN エンドポイント内のユーザー geo アクセスを定義するルール。</span><span class="sxs-lookup"><span data-stu-id="29d7d-101">Rules defining user geo access within a CDN endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29d7d-102">GeoFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29d7d-102">Initializes a new instance of the GeoFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, System.Collections.Generic.IList&lt;string&gt; countryCodes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class System.Collections.Generic.IList`1&lt;string&gt; countryCodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.#ctor(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (relativePath As String, action As GeoFilterActions, countryCodes As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter (relativePath, action, countryCodes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions" />
        <Parameter Name="countryCodes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="relativePath"><span data-ttu-id="29d7d-103">地理的フィルターに適用可能な相対パスです。</span><span class="sxs-lookup"><span data-stu-id="29d7d-103">Relative path applicable to geo filter.</span></span>
            <span data-ttu-id="29d7d-104">(例: '/マイ ピクチャ、'/mypicture/kitty.jpg'、およびなどです)。</span><span class="sxs-lookup"><span data-stu-id="29d7d-104">(e.g. '/mypictures', '/mypicture/kitty.jpg', and etc.)</span></span></param>
        <param name="action"><span data-ttu-id="29d7d-105">アクション、geo のフィルター処理、つまり、許可またはアクセスをブロックします。</span><span class="sxs-lookup"><span data-stu-id="29d7d-105">Action of the geo filter, i.e. allow or block access.</span></span> <span data-ttu-id="29d7d-106">使用可能な値が含まれます: 'ブロック'、'Allow'</span><span class="sxs-lookup"><span data-stu-id="29d7d-106">Possible values include: 'Block', 'Allow'</span></span></param>
        <param name="countryCodes"><span data-ttu-id="29d7d-107">地理的に国のユーザー アクセスを定義する 2 つの文字の国コードをフィルター処理、オーストラリアなど、MX、米国。</span><span class="sxs-lookup"><span data-stu-id="29d7d-107">Two letter country codes defining user country access in a geo filter, e.g. AU, MX, US.</span></span></param>
        <summary>
            <span data-ttu-id="29d7d-108">GeoFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29d7d-108">Initializes a new instance of the GeoFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As GeoFilterActions" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d7d-109">取得または設定、geo のアクションをフィルター処理、つまり、許可またはアクセスをブロックします。</span><span class="sxs-lookup"><span data-stu-id="29d7d-109">Gets or sets action of the geo filter, i.e. allow or block access.</span></span>
            <span data-ttu-id="29d7d-110">使用可能な値が含まれます: 'ブロック'、'Allow'</span><span class="sxs-lookup"><span data-stu-id="29d7d-110">Possible values include: 'Block', 'Allow'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountryCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CountryCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CountryCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.CountryCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property CountryCodes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CountryCodes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.CountryCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="countryCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d7d-111">取得または 2 つの文字の国コード、地理的フィルターで、国のユーザー アクセスを定義するオーストラリア、MX、米国などを設定します。</span><span class="sxs-lookup"><span data-stu-id="29d7d-111">Gets or sets two letter country codes defining user country access in a geo filter, e.g. AU, MX, US.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativePath">
      <MemberSignature Language="C#" Value="public string RelativePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.RelativePath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativePath As String" />
      <MemberSignature Language="F#" Value="member this.RelativePath : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.RelativePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29d7d-112">取得または、地理的フィルターに適用可能な相対パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="29d7d-112">Gets or sets relative path applicable to geo filter.</span></span> <span data-ttu-id="29d7d-113">(例: '/マイ ピクチャ、'/mypicture/kitty.jpg'、およびなどです)。</span><span class="sxs-lookup"><span data-stu-id="29d7d-113">(e.g. '/mypictures', '/mypicture/kitty.jpg', and etc.)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="geoFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29d7d-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="29d7d-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="29d7d-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="29d7d-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>