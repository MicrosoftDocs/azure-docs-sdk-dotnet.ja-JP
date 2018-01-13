<Type Name="PoolUpdatePropertiesOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions">
  <TypeSignature Language="C#" Value="public class PoolUpdatePropertiesOptions : Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUpdatePropertiesOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUpdatePropertiesOptions&#xA;Implements ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type PoolUpdatePropertiesOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            UpdateProperties 操作に追加のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpdatePropertiesOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PoolUpdatePropertiesOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpdatePropertiesOptions (Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.#ctor(System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions : Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions (timeout, clientRequestId, returnClientRequestId, ocpDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="returnClientRequestId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="timeout">最大時間を秒単位で、要求の処理に、サーバーが費やすことができます。 既定値は 30 秒です。</param>
        <param name="clientRequestId">例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式で、呼び出し元によって生成された要求 id-4 CD 3-8152-34347DC9F2B0 です。</param>
        <param name="returnClientRequestId">サーバーが応答でクライアント要求 id を返すかどうか。</param>
        <param name="ocpDate">要求が発行された時刻。 クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。</param>
        <summary>
            PoolUpdatePropertiesOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式では呼び出し元によって生成された要求 id が設定を取得または -4 CD 3-8152-34347DC9F2B0 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.OcpDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求が発行された時刻を設定します。 クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.ReturnClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ReturnClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサーバーが応答でクライアント要求 id を返すかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions.Timeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions.Timeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の最大時間 (秒)、要求の処理に、サーバーが費やすことができます。 既定値は 30 秒です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>