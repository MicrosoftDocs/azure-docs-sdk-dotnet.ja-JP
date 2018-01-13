<Type Name="PushSettings" FullName="Microsoft.Azure.Management.WebSites.Models.PushSettings">
  <TypeSignature Language="C#" Value="public class PushSettings : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PushSettings extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.PushSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PushSettings&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type PushSettings = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
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
            アプリの設定をプッシュします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PushSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PushSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PushSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PushSettings (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; isPushEnabled = null, string tagWhitelistJson = null, string tagsRequiringAuth = null, string dynamicTagsJson = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; isPushEnabled, string tagWhitelistJson, string tagsRequiringAuth, string dynamicTagsJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PushSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional isPushEnabled As Nullable(Of Boolean) = null, Optional tagWhitelistJson As String = null, Optional tagsRequiringAuth As String = null, Optional dynamicTagsJson As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.PushSettings : string * string * string * string * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.PushSettings" Usage="new Microsoft.Azure.Management.WebSites.Models.PushSettings (id, name, kind, type, isPushEnabled, tagWhitelistJson, tagsRequiringAuth, dynamicTagsJson)" />
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
        <Parameter Name="isPushEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="tagWhitelistJson" Type="System.String" />
        <Parameter Name="tagsRequiringAuth" Type="System.String" />
        <Parameter Name="dynamicTagsJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="isPushEnabled">取得またはプッシュ エンドポイントが有効になっているかどうかを示すフラグを設定します。</param>
        <param name="tagWhitelistJson">取得またはホワイト リストに登録プッシュ登録エンドポイントで使用するためにあるタグの一覧を含む JSON 文字列を設定します。</param>
        <param name="tagsRequiringAuth">取得またはプッシュ登録エンドポイントで使用されるユーザー認証を必要とするタグの一覧を含む JSON 文字列を設定します。
            タグは、英数字と次で構成できます: '_'、' @'、'#'、'. ',':'、'-' です。
            PushRequestHandler で検証を実行する必要があります。</param>
        <param name="dynamicTagsJson">取得またはプッシュ登録エンドポイントのユーザー要求からに評価される動的のタグの一覧を含む JSON 文字列を設定します。</param>
        <summary>
            PushSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicTagsJson">
      <MemberSignature Language="C#" Value="public string DynamicTagsJson { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DynamicTagsJson" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.DynamicTagsJson" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicTagsJson As String" />
      <MemberSignature Language="F#" Value="member this.DynamicTagsJson : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.DynamicTagsJson" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dynamicTagsJson")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプッシュ登録エンドポイントのユーザー要求からに評価される動的のタグの一覧を含む JSON 文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPushEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPushEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPushEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.IsPushEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPushEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPushEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.IsPushEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isPushEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプッシュ エンドポイントが有効になっているかどうかを示すフラグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagsRequiringAuth">
      <MemberSignature Language="C#" Value="public string TagsRequiringAuth { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagsRequiringAuth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.TagsRequiringAuth" />
      <MemberSignature Language="VB.NET" Value="Public Property TagsRequiringAuth As String" />
      <MemberSignature Language="F#" Value="member this.TagsRequiringAuth : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.TagsRequiringAuth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tagsRequiringAuth")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプッシュ登録エンドポイントで使用されるユーザー認証を必要とするタグの一覧を含む JSON 文字列を設定します。
            タグは、英数字と次で構成できます: '_'、' @'、'#'、'. ',':'、'-' です。
            PushRequestHandler で検証を実行する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagWhitelistJson">
      <MemberSignature Language="C#" Value="public string TagWhitelistJson { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagWhitelistJson" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.TagWhitelistJson" />
      <MemberSignature Language="VB.NET" Value="Public Property TagWhitelistJson As String" />
      <MemberSignature Language="F#" Value="member this.TagWhitelistJson : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.TagWhitelistJson" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tagWhitelistJson")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはホワイト リストに登録プッシュ登録エンドポイントで使用するためにあるタグの一覧を含む JSON 文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>