<Type Name="NextHopParametersInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner">
  <TypeSignature Language="C#" Value="public class NextHopParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NextHopParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class NextHopParametersInner" />
  <TypeSignature Language="F#" Value="type NextHopParametersInner = class" />
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
            送信元と送信先のエンドポイントを定義するパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NextHopParametersInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopParametersInner (string targetResourceId, string sourceIPAddress, string destinationIPAddress, string targetNicResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string sourceIPAddress, string destinationIPAddress, string targetNicResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, sourceIPAddress As String, destinationIPAddress As String, Optional targetNicResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner : string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner (targetResourceId, sourceIPAddress, destinationIPAddress, targetNicResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="sourceIPAddress" Type="System.String" />
        <Parameter Name="destinationIPAddress" Type="System.String" />
        <Parameter Name="targetNicResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId">アクションの実行対象となるターゲット リソースのリソースの識別子です。</param>
        <param name="sourceIPAddress">発信元 IP アドレス。</param>
        <param name="destinationIPAddress">宛先 IP アドレス。</param>
        <param name="targetNicResourceId">NIC の id。 (が複数の Nic の VM nic には、いずれかを IP 転送が有効になっている場合は、し、このパラメーター指定してください。 それ以外の場合省略可能)。</param>
        <summary>
            NextHopParametersInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationIPAddress">
      <MemberSignature Language="C#" Value="public string DestinationIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.DestinationIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.DestinationIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.DestinationIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または宛先 IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceIPAddress">
      <MemberSignature Language="C#" Value="public string SourceIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.SourceIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.SourceIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.SourceIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または送信元 IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNicResourceId">
      <MemberSignature Language="C#" Value="public string TargetNicResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetNicResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetNicResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNicResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetNicResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetNicResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNicResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、NIC の id です。 (が複数の Nic の VM nic には、いずれかを IP 転送が有効になっている場合は、し、このパラメーター指定してください。 それ以外の場合省略可能)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、アクションの実行対象となるターゲット リソースのリソース識別子。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nextHopParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>