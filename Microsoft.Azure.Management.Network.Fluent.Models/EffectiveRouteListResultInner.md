<Type Name="EffectiveRouteListResultInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner">
  <TypeSignature Language="C#" Value="public class EffectiveRouteListResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveRouteListResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveRouteListResultInner" />
  <TypeSignature Language="F#" Value="type EffectiveRouteListResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            リストの有効なルート API サービスの応答を呼び出します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRouteListResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            EffectiveRouteListResultInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRouteListResultInner (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt; value = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of EffectiveRoute) = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt; * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value">有効なルートの一覧。</param>
        <param name="nextLink">次の結果セットを取得する URL です。</param>
        <summary>
            EffectiveRouteListResultInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または次の結果セットを取得する URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of EffectiveRoute)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRoute&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または有効なルートの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>