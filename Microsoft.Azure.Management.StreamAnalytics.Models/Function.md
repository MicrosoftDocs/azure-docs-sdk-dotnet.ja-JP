<Type Name="Function" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Function">
  <TypeSignature Language="C#" Value="public class Function : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Function extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
  <TypeSignature Language="VB.NET" Value="Public Class Function&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Function = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e4d01-101">名前付きの関数に関連付けられているすべての情報を含む関数オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e4d01-101">A function object, containing all information associated with the named function.</span></span> <span data-ttu-id="e4d01-102">ストリーミング ジョブの下では、すべての関数が含まれています。</span><span class="sxs-lookup"><span data-stu-id="e4d01-102">All functions are contained under a streaming job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Function ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Function.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e4d01-103">関数クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e4d01-103">Initializes a new instance of the Function class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Function (string id = null, string name = null, string type = null, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Function.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional properties As FunctionProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Function : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Function (id, name, type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e4d01-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="e4d01-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="e4d01-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="e4d01-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="e4d01-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="e4d01-106">Resource type</span></span></param>
        <param name="properties"><span data-ttu-id="e4d01-107">関数に関連付けられているプロパティです。</span><span class="sxs-lookup"><span data-stu-id="e4d01-107">The properties that are associated with a function.</span></span></param>
        <summary>
            <span data-ttu-id="e4d01-108">関数クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e4d01-108">Initializes a new instance of the Function class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Function.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As FunctionProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Function.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4d01-109">取得または関数に関連付けられているプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="e4d01-109">Gets or sets the properties that are associated with a function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>