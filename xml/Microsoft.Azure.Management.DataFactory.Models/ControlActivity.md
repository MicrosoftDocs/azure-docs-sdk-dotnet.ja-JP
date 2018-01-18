<Type Name="ControlActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.ControlActivity">
  <TypeSignature Language="C#" Value="public class ControlActivity : Microsoft.Azure.Management.DataFactory.Models.Activity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ControlActivity extends Microsoft.Azure.Management.DataFactory.Models.Activity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ControlActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class ControlActivity&#xA;Inherits Activity" />
  <TypeSignature Language="F#" Value="type ControlActivity = class&#xA;    inherit Activity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Activity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Container")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="48af3-101">コントロールのすべてのアクティビティの基本クラスでは、まで IfCondition、ForEach と同様にします。</span><span class="sxs-lookup"><span data-stu-id="48af3-101">Base class for all control activities like IfCondition, ForEach , Until.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ControlActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ControlActivity.#ctor" />
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
            <span data-ttu-id="48af3-102">ControlActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="48af3-102">Initializes a new instance of the ControlActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ControlActivity (string name, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ControlActivity.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ControlActivity : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.ControlActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.ControlActivity (name, additionalProperties, description, dependsOn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="48af3-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="48af3-103">Activity name.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="48af3-104">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="48af3-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="48af3-105">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="48af3-105">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="48af3-106">アクティビティは、条件によって異なります。</span><span class="sxs-lookup"><span data-stu-id="48af3-106">Activity depends on condition.</span></span></param>
        <summary>
            <span data-ttu-id="48af3-107">ControlActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="48af3-107">Initializes a new instance of the ControlActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ControlActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="controlActivity.Validate " />
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
            <span data-ttu-id="48af3-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="48af3-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="48af3-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="48af3-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>