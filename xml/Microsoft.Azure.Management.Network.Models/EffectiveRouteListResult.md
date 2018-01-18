<Type Name="EffectiveRouteListResult" FullName="Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult">
  <TypeSignature Language="C#" Value="public class EffectiveRouteListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveRouteListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveRouteListResult" />
  <TypeSignature Language="F#" Value="type EffectiveRouteListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="20acf-101">リストの有効なルート API サービスの応答を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="20acf-101">Response for list effective route API service call.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRouteListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20acf-102">EffectiveRouteListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20acf-102">Initializes a new instance of the EffectiveRouteListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRouteListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt; value = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.EffectiveRoute},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of EffectiveRoute) = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult" Usage="new Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="20acf-103">有効なルートの一覧。</span><span class="sxs-lookup"><span data-stu-id="20acf-103">A list of effective routes.</span></span></param>
        <param name="nextLink"><span data-ttu-id="20acf-104">次の結果セットを取得する URL です。</span><span class="sxs-lookup"><span data-stu-id="20acf-104">The URL to get the next set of results.</span></span></param>
        <summary>
            <span data-ttu-id="20acf-105">EffectiveRouteListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20acf-105">Initializes a new instance of the EffectiveRouteListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20acf-106">次の結果セットを取得する URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="20acf-106">Gets the URL to get the next set of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of EffectiveRoute)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRouteListResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.EffectiveRoute&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20acf-107">取得または有効なルートの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="20acf-107">Gets or sets a list of effective routes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>