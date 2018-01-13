<Type Name="SiteSealRequest" FullName="Microsoft.Azure.Management.WebSites.Models.SiteSealRequest">
  <TypeSignature Language="C#" Value="public class SiteSealRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteSealRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteSealRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteSealRequest" />
  <TypeSignature Language="F#" Value="type SiteSealRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7f65d-101">サイトでは、要求を封印します。</span><span class="sxs-lookup"><span data-stu-id="7f65d-101">Site seal request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSealRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSealRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7f65d-102">SiteSealRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f65d-102">Initializes a new instance of the SiteSealRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSealRequest (Nullable&lt;bool&gt; lightTheme = null, string locale = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; lightTheme, string locale) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSealRequest.#ctor(System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lightTheme As Nullable(Of Boolean) = null, Optional locale As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteSealRequest : Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.SiteSealRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteSealRequest (lightTheme, locale)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lightTheme" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="locale" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lightTheme"><span data-ttu-id="7f65d-103">場合&lt;コード&gt;true&lt;/code&gt;封印するサイトの明るい配色テーマを使用し、それ以外の場合、既定の色のテーマを使用します。</span><span class="sxs-lookup"><span data-stu-id="7f65d-103">If &lt;code&gt;true&lt;/code&gt; use the light color theme for site seal; otherwise, use the default color theme.</span></span></param>
        <param name="locale"><span data-ttu-id="7f65d-104">封印するサイトのロケールです。</span><span class="sxs-lookup"><span data-stu-id="7f65d-104">Locale of site seal.</span></span></param>
        <summary>
            <span data-ttu-id="7f65d-105">SiteSealRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f65d-105">Initializes a new instance of the SiteSealRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LightTheme">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LightTheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LightTheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSealRequest.LightTheme" />
      <MemberSignature Language="VB.NET" Value="Public Property LightTheme As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LightTheme : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSealRequest.LightTheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lightTheme")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f65d-106">場合取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; サイトの封印の明るい配色テーマを使用して; それ以外の場合、既定の色のテーマを使用します。</span><span class="sxs-lookup"><span data-stu-id="7f65d-106">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; use the light color theme for site seal; otherwise, use the default color theme.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locale">
      <MemberSignature Language="C#" Value="public string Locale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Locale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSealRequest.Locale" />
      <MemberSignature Language="VB.NET" Value="Public Property Locale As String" />
      <MemberSignature Language="F#" Value="member this.Locale : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSealRequest.Locale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f65d-107">取得またはサイトの封印のロケールを設定します。</span><span class="sxs-lookup"><span data-stu-id="7f65d-107">Gets or sets locale of site seal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>