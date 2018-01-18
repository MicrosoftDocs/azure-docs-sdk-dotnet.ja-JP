<Type Name="VirtualApplication" FullName="Microsoft.Azure.Management.WebSites.Models.VirtualApplication">
  <TypeSignature Language="C#" Value="public class VirtualApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualApplication extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VirtualApplication" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualApplication" />
  <TypeSignature Language="F#" Value="type VirtualApplication = class" />
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
            <span data-ttu-id="e5c6d-101">アプリ内で仮想アプリケーション。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-101">Virtual application in an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualApplication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VirtualApplication.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e5c6d-102">VirtualApplication クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-102">Initializes a new instance of the VirtualApplication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualApplication (string virtualPath = null, string physicalPath = null, Nullable&lt;bool&gt; preloadEnabled = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt; virtualDirectories = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string virtualPath, string physicalPath, valuetype System.Nullable`1&lt;bool&gt; preloadEnabled, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt; virtualDirectories) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VirtualApplication.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.VirtualDirectory})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional virtualPath As String = null, Optional physicalPath As String = null, Optional preloadEnabled As Nullable(Of Boolean) = null, Optional virtualDirectories As IList(Of VirtualDirectory) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VirtualApplication : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.VirtualApplication" Usage="new Microsoft.Azure.Management.WebSites.Models.VirtualApplication (virtualPath, physicalPath, preloadEnabled, virtualDirectories)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualPath" Type="System.String" />
        <Parameter Name="physicalPath" Type="System.String" />
        <Parameter Name="preloadEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="virtualDirectories" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt;" />
      </Parameters>
      <Docs>
        <param name="virtualPath"><span data-ttu-id="e5c6d-103">仮想パス。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-103">Virtual path.</span></span></param>
        <param name="physicalPath"><span data-ttu-id="e5c6d-104">物理パス。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-104">Physical path.</span></span></param>
        <param name="preloadEnabled"><span data-ttu-id="e5c6d-105">&lt;コード&gt;true&lt;/code&gt;プリロードが有効である場合は、それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-105">&lt;code&gt;true&lt;/code&gt; if preloading is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="virtualDirectories"><span data-ttu-id="e5c6d-106">仮想アプリケーション用の仮想ディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-106">Virtual directories for virtual application.</span></span></param>
        <summary>
            <span data-ttu-id="e5c6d-107">VirtualApplication クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-107">Initializes a new instance of the VirtualApplication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PhysicalPath">
      <MemberSignature Language="C#" Value="public string PhysicalPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PhysicalPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VirtualApplication.PhysicalPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PhysicalPath As String" />
      <MemberSignature Language="F#" Value="member this.PhysicalPath : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VirtualApplication.PhysicalPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="physicalPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5c6d-108">取得または物理パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-108">Gets or sets physical path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreloadEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PreloadEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PreloadEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VirtualApplication.PreloadEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property PreloadEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PreloadEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VirtualApplication.PreloadEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preloadEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5c6d-109">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; プリロードが有効である場合は、それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-109">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if preloading is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt; VirtualDirectories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt; VirtualDirectories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VirtualApplication.VirtualDirectories" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualDirectories As IList(Of VirtualDirectory)" />
      <MemberSignature Language="F#" Value="member this.VirtualDirectories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VirtualApplication.VirtualDirectories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualDirectories")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualDirectory&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5c6d-110">取得または、仮想アプリケーション用の仮想ディレクトリを設定します。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-110">Gets or sets virtual directories for virtual application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualPath">
      <MemberSignature Language="C#" Value="public string VirtualPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VirtualApplication.VirtualPath" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualPath As String" />
      <MemberSignature Language="F#" Value="member this.VirtualPath : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VirtualApplication.VirtualPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5c6d-111">取得または仮想パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e5c6d-111">Gets or sets virtual path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>