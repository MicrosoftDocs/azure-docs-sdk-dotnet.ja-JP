<Type Name="NextHopResult" FullName="Microsoft.Azure.Management.Network.Models.NextHopResult">
  <TypeSignature Language="C#" Value="public class NextHopResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NextHopResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NextHopResult" />
  <TypeSignature Language="VB.NET" Value="Public Class NextHopResult" />
  <TypeSignature Language="F#" Value="type NextHopResult = class" />
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
            指定した VM から次のホップ先に関する情報。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NextHopResult.#ctor" />
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
            NextHopResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopResult (string nextHopType = null, string nextHopIpAddress = null, string routeTableId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextHopType, string nextHopIpAddress, string routeTableId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NextHopResult.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nextHopType As String = null, Optional nextHopIpAddress As String = null, Optional routeTableId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NextHopResult : string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NextHopResult" Usage="new Microsoft.Azure.Management.Network.Models.NextHopResult (nextHopType, nextHopIpAddress, routeTableId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextHopType" Type="System.String" />
        <Parameter Name="nextHopIpAddress" Type="System.String" />
        <Parameter Name="routeTableId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nextHopType">次ホップの種類。 使用可能な値が含まれます: 'Internet'、'VirtualAppliance'、'VirtualNetworkGateway'、'VnetLocal'、'HyperNetGateway'、'None'</param>
        <param name="nextHopIpAddress">次ホップ IP アドレス</param>
        <param name="routeTableId">返されるルートに関連付けられているルート テーブルのリソース識別子。 返されるルートがルートを作成したすべてのユーザーに対応していない場合、このフィールドは文字列になります、' システム ルート ' です。</param>
        <summary>
            NextHopResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIpAddress">
      <MemberSignature Language="C#" Value="public string NextHopIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NextHopResult.NextHopIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.NextHopIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NextHopResult.NextHopIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または次ホップ IP アドレスを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopType">
      <MemberSignature Language="C#" Value="public string NextHopType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NextHopResult.NextHopType" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopType As String" />
      <MemberSignature Language="F#" Value="member this.NextHopType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NextHopResult.NextHopType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または次ホップの種類を設定します。 使用可能な値が含まれます: 'Internet'、'VirtualAppliance'、'VirtualNetworkGateway'、'VnetLocal'、'HyperNetGateway'、'None'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTableId">
      <MemberSignature Language="C#" Value="public string RouteTableId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RouteTableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NextHopResult.RouteTableId" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteTableId As String" />
      <MemberSignature Language="F#" Value="member this.RouteTableId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NextHopResult.RouteTableId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routeTableId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または返されるルートに関連付けられているルート テーブルのリソース識別子を設定します。 返されるルートがルートを作成したすべてのユーザーに対応していない場合、このフィールドは文字列になります、' システム ルート ' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>