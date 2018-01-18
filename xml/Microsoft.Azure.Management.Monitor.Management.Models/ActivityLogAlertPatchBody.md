<Type Name="ActivityLogAlertPatchBody" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody">
  <TypeSignature Language="C#" Value="public class ActivityLogAlertPatchBody" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityLogAlertPatchBody extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityLogAlertPatchBody" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertPatchBody = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a5bc2-101">アクティビティ ログ アラート オブジェクト patch 操作の本文。</span><span class="sxs-lookup"><span data-stu-id="a5bc2-101">An activity log alert object for the body of patch operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertPatchBody ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5bc2-102">ActivityLogAlertPatchBody クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5bc2-102">Initializes a new instance of the ActivityLogAlertPatchBody class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertPatchBody (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody : System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody (tags, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="a5bc2-103">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="a5bc2-103">Resource tags</span></span></param>
        <param name="enabled"><span data-ttu-id="a5bc2-104">このアクティビティのログのアラートが有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a5bc2-104">Indicates whether this activity log alert is enabled.</span></span> <span data-ttu-id="a5bc2-105">アクティビティのログのアラートが有効でない場合、そのアクションのいずれもアクティブ化されます。</span><span class="sxs-lookup"><span data-stu-id="a5bc2-105">If an activity log alert is not enabled, then none of its actions will be activated.</span></span></param>
        <summary>
            <span data-ttu-id="a5bc2-106">ActivityLogAlertPatchBody クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5bc2-106">Initializes a new instance of the ActivityLogAlertPatchBody class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5bc2-107">取得または設定は、このアクティビティのログのアラートが有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a5bc2-107">Gets or sets indicates whether this activity log alert is enabled.</span></span>
            <span data-ttu-id="a5bc2-108">アクティビティのログのアラートが有効でない場合、そのアクションのいずれもアクティブ化されます。</span><span class="sxs-lookup"><span data-stu-id="a5bc2-108">If an activity log alert is not enabled, then none of its actions will be activated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5bc2-109">取得またはリソース タグを設定</span><span class="sxs-lookup"><span data-stu-id="a5bc2-109">Gets or sets resource tags</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>