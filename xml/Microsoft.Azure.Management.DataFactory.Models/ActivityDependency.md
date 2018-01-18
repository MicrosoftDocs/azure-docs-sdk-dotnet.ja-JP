<Type Name="ActivityDependency" FullName="Microsoft.Azure.Management.DataFactory.Models.ActivityDependency">
  <TypeSignature Language="C#" Value="public class ActivityDependency" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityDependency extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ActivityDependency" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityDependency" />
  <TypeSignature Language="F#" Value="type ActivityDependency = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b2dca-101">アクティビティの依存関係情報です。</span><span class="sxs-lookup"><span data-stu-id="b2dca-101">Activity dependency information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityDependency ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b2dca-102">ActivityDependency クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b2dca-102">Initializes a new instance of the ActivityDependency class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityDependency (string activity, System.Collections.Generic.IList&lt;string&gt; dependencyConditions, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string activity, class System.Collections.Generic.IList`1&lt;string&gt; dependencyConditions, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activity As String, dependencyConditions As IList(Of String), Optional additionalProperties As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ActivityDependency : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.ActivityDependency" Usage="new Microsoft.Azure.Management.DataFactory.Models.ActivityDependency (activity, dependencyConditions, additionalProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activity" Type="System.String" />
        <Parameter Name="dependencyConditions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="activity"><span data-ttu-id="b2dca-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="b2dca-103">Activity name.</span></span></param>
        <param name="dependencyConditions"><span data-ttu-id="b2dca-104">依存関係の場合は、一致条件です。</span><span class="sxs-lookup"><span data-stu-id="b2dca-104">Match-Condition for the dependency.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="b2dca-105">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="b2dca-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <summary>
            <span data-ttu-id="b2dca-106">ActivityDependency クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b2dca-106">Initializes a new instance of the ActivityDependency class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Activity">
      <MemberSignature Language="C#" Value="public string Activity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Activity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.Activity" />
      <MemberSignature Language="VB.NET" Value="Public Property Activity As String" />
      <MemberSignature Language="F#" Value="member this.Activity : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.Activity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2dca-107">取得またはアクティビティの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2dca-107">Gets or sets activity name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2dca-108">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="b2dca-108">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependencyConditions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DependencyConditions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DependencyConditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.DependencyConditions" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyConditions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DependencyConditions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.DependencyConditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependencyConditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2dca-109">取得または依存関係の一致条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2dca-109">Gets or sets match-Condition for the dependency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityDependency.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="activityDependency.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b2dca-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="b2dca-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2dca-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2dca-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>