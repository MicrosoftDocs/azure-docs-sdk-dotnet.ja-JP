<Type Name="ExpressRouteCircuitRoutesTableSummary" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitRoutesTableSummary" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitRoutesTableSummary extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitRoutesTableSummary" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitRoutesTableSummary = class" />
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
            ExpressRouteCircuit に関連付けられているルート テーブル。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitRoutesTableSummary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ExpressRouteCircuitRoutesTableSummary クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitRoutesTableSummary (string neighbor = null, Nullable&lt;int&gt; v = null, Nullable&lt;int&gt; asProperty = null, string upDown = null, string statePfxRcd = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string neighbor, valuetype System.Nullable`1&lt;int32&gt; v, valuetype System.Nullable`1&lt;int32&gt; asProperty, string upDown, string statePfxRcd) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional neighbor As String = null, Optional v As Nullable(Of Integer) = null, Optional asProperty As Nullable(Of Integer) = null, Optional upDown As String = null, Optional statePfxRcd As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary (neighbor, v, asProperty, upDown, statePfxRcd)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="neighbor" Type="System.String" />
        <Parameter Name="v" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="asProperty" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="upDown" Type="System.String" />
        <Parameter Name="statePfxRcd" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="neighbor">近隣ノード</param>
        <param name="v">近隣ノードに読み上げ BGP バージョン番号です。</param>
        <param name="asProperty">自律システム番号。</param>
        <param name="upDown">BGP セッションが確立した状態にされていない場合、設定された状態、または現在の状態にされている時間の長さ。</param>
        <param name="statePfxRcd">BGP セッション、および、近隣ノードまたはピア グループから受信したプレフィックスの数の現在の状態。</param>
        <summary>
            ExpressRouteCircuitRoutesTableSummary クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsProperty">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AsProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AsProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.AsProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property AsProperty As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AsProperty : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.AsProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="as")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または自律システム番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Neighbor">
      <MemberSignature Language="C#" Value="public string Neighbor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Neighbor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.Neighbor" />
      <MemberSignature Language="VB.NET" Value="Public Property Neighbor As String" />
      <MemberSignature Language="F#" Value="member this.Neighbor : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.Neighbor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="neighbor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の近隣ノード
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatePfxRcd">
      <MemberSignature Language="C#" Value="public string StatePfxRcd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatePfxRcd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.StatePfxRcd" />
      <MemberSignature Language="VB.NET" Value="Public Property StatePfxRcd As String" />
      <MemberSignature Language="F#" Value="member this.StatePfxRcd : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.StatePfxRcd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statePfxRcd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または BGP セッションの現在の状態と、近隣ノードまたはピア グループから受信したプレフィックスの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpDown">
      <MemberSignature Language="C#" Value="public string UpDown { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpDown" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.UpDown" />
      <MemberSignature Language="VB.NET" Value="Public Property UpDown As String" />
      <MemberSignature Language="F#" Value="member this.UpDown : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.UpDown" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="upDown")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定された状態にされていない場合、設定された状態、または現在の状態で、BGP セッションがしている時間の長さを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="V">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; V { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; V" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.V" />
      <MemberSignature Language="VB.NET" Value="Public Property V As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.V : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitRoutesTableSummary.V" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="v")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または近隣ノードの音声の BGP バージョン番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>