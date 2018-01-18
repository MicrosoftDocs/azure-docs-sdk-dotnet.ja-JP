<Type Name="Region" FullName="Microsoft.Azure.Management.TrafficManager.Models.Region">
  <TypeSignature Language="C#" Value="public class Region" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Region extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.Region" />
  <TypeSignature Language="VB.NET" Value="Public Class Region" />
  <TypeSignature Language="F#" Value="type Region = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b26b7-101">地理的なトラフィックのルーティング メソッドで使用される、地理的な階層内の領域を表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="b26b7-101">Class representing a region in the Geographic hierarchy used with the Geographic traffic routing method.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Region ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Region.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b26b7-102">領域クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b26b7-102">Initializes a new instance of the Region class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Region (string code = null, string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; regions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Region&gt; regions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Region.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.TrafficManager.Models.Region})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional name As String = null, Optional regions As IList(Of Region) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.Region : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.Region" Usage="new Microsoft.Azure.Management.TrafficManager.Models.Region (code, name, regions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="regions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="b26b7-103">地域コード</span><span class="sxs-lookup"><span data-stu-id="b26b7-103">The code of the region</span></span></param>
        <param name="name"><span data-ttu-id="b26b7-104">領域の名前</span><span class="sxs-lookup"><span data-stu-id="b26b7-104">The name of the region</span></span></param>
        <param name="regions"><span data-ttu-id="b26b7-105">リージョンの一覧は、地理的な階層内のこの領域でグループ化。</span><span class="sxs-lookup"><span data-stu-id="b26b7-105">The list of Regions grouped under this Region in the Geographic Hierarchy.</span></span></param>
        <summary>
            <span data-ttu-id="b26b7-106">領域クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b26b7-106">Initializes a new instance of the Region class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Region.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Region.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b26b7-107">コード領域の取得または設定</span><span class="sxs-lookup"><span data-stu-id="b26b7-107">Gets or sets the code of the region</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Region.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Region.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b26b7-108">取得または設定の領域の名前</span><span class="sxs-lookup"><span data-stu-id="b26b7-108">Gets or sets the name of the region</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Regions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; Regions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Region&gt; Regions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Region.Regions" />
      <MemberSignature Language="VB.NET" Value="Public Property Regions As IList(Of Region)" />
      <MemberSignature Language="F#" Value="member this.Regions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Region.Regions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="regions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b26b7-109">取得または地理的な階層内のこの領域でグループ化されているリージョンの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="b26b7-109">Gets or sets the list of Regions grouped under this Region in the Geographic Hierarchy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>