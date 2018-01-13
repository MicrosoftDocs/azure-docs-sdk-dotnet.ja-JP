<Type Name="SlotSwapStatus" FullName="Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus">
  <TypeSignature Language="C#" Value="public class SlotSwapStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SlotSwapStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class SlotSwapStatus" />
  <TypeSignature Language="F#" Value="type SlotSwapStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            最後に成功したスロット スワップ操作の状態です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlotSwapStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SlotSwapStatus クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlotSwapStatus (Nullable&lt;DateTime&gt; timestampUtc = null, string sourceSlotName = null, string destinationSlotName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestampUtc, string sourceSlotName, string destinationSlotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.#ctor(System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timestampUtc As Nullable(Of DateTime) = null, Optional sourceSlotName As String = null, Optional destinationSlotName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus : Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" Usage="new Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus (timestampUtc, sourceSlotName, destinationSlotName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timestampUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sourceSlotName" Type="System.String" />
        <Parameter Name="destinationSlotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timestampUtc">最後の正常なスロット スワップの完了した時刻。</param>
        <param name="sourceSlotName">最後のスワップ操作のソース スロットです。</param>
        <param name="destinationSlotName">最後のスワップ操作の送信先スロット。</param>
        <summary>
            SlotSwapStatus クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationSlotName">
      <MemberSignature Language="C#" Value="public string DestinationSlotName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationSlotName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.DestinationSlotName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DestinationSlotName As String" />
      <MemberSignature Language="F#" Value="member this.DestinationSlotName : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.DestinationSlotName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationSlotName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最後のスワップ操作の送信先スロットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceSlotName">
      <MemberSignature Language="C#" Value="public string SourceSlotName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceSlotName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.SourceSlotName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceSlotName As String" />
      <MemberSignature Language="F#" Value="member this.SourceSlotName : string" Usage="Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.SourceSlotName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceSlotName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最後のスワップ操作の元のスロットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimestampUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.TimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimestampUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus.TimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestampUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最後の正常なスロット スワップの完了した時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>