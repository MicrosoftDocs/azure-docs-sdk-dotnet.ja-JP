<Type Name="SiteSourceControl" FullName="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl">
  <TypeSignature Language="C#" Value="public class SiteSourceControl : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteSourceControl extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteSourceControl&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteSourceControl = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            アプリのソース コントロールの構成です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SiteSourceControl クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSourceControl (string id = null, string name = null, string kind = null, string type = null, string repoUrl = null, string branch = null, Nullable&lt;bool&gt; isManualIntegration = null, Nullable&lt;bool&gt; deploymentRollbackEnabled = null, Nullable&lt;bool&gt; isMercurial = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string repoUrl, string branch, valuetype System.Nullable`1&lt;bool&gt; isManualIntegration, valuetype System.Nullable`1&lt;bool&gt; deploymentRollbackEnabled, valuetype System.Nullable`1&lt;bool&gt; isMercurial) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional repoUrl As String = null, Optional branch As String = null, Optional isManualIntegration As Nullable(Of Boolean) = null, Optional deploymentRollbackEnabled As Nullable(Of Boolean) = null, Optional isMercurial As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteSourceControl : string * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SiteSourceControl" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteSourceControl (id, name, kind, type, repoUrl, branch, isManualIntegration, deploymentRollbackEnabled, isMercurial)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="repoUrl" Type="System.String" />
        <Parameter Name="branch" Type="System.String" />
        <Parameter Name="isManualIntegration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="deploymentRollbackEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isMercurial" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="repoUrl">リポジトリまたはソース コントロールの URL です。</param>
        <param name="branch">展開に使用する分岐の名前。</param>
        <param name="isManualIntegration">&lt;コード&gt;true&lt;/code&gt;手動の統合を制限するには&lt;コード&gt;false&lt;/code&gt; (を webhook を構成できる、GitHub のようなオンラインのリポジトリに) 継続的な統合を有効にします。</param>
        <param name="deploymentRollbackEnabled">&lt;コード&gt;true&lt;/code&gt;展開のロールバックを有効にするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="isMercurial">&lt;コード&gt;true&lt;/code&gt; Mercurial リポジトリです。&lt;コード&gt;false&lt;/code&gt; Git リポジトリ用です。</param>
        <summary>
            SiteSourceControl クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Branch">
      <MemberSignature Language="C#" Value="public string Branch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Branch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.Branch" />
      <MemberSignature Language="VB.NET" Value="Public Property Branch As String" />
      <MemberSignature Language="F#" Value="member this.Branch : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.Branch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.branch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または展開に使用する分岐の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentRollbackEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeploymentRollbackEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeploymentRollbackEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.DeploymentRollbackEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentRollbackEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeploymentRollbackEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.DeploymentRollbackEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deploymentRollbackEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 展開のロールバックを有効にするそれ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManualIntegration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsManualIntegration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsManualIntegration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsManualIntegration" />
      <MemberSignature Language="VB.NET" Value="Public Property IsManualIntegration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsManualIntegration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsManualIntegration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isManualIntegration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; を手動で統合; に制限するには&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt; (を webhook を構成できる、GitHub のようなオンラインのリポジトリに) 継続的な統合を有効にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsMercurial">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsMercurial { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsMercurial" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsMercurial" />
      <MemberSignature Language="VB.NET" Value="Public Property IsMercurial As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsMercurial : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsMercurial" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isMercurial")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; Mercurial リポジトリです。&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt; Git リポジトリのです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepoUrl">
      <MemberSignature Language="C#" Value="public string RepoUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepoUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.RepoUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property RepoUrl As String" />
      <MemberSignature Language="F#" Value="member this.RepoUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.RepoUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.repoUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリポジトリまたはソース コントロールの URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>