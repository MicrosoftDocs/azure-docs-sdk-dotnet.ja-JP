<Type Name="TriggerRun" FullName="Microsoft.Azure.Management.DataFactory.Models.TriggerRun">
  <TypeSignature Language="C#" Value="public class TriggerRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggerRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TriggerRun" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggerRun" />
  <TypeSignature Language="F#" Value="type TriggerRun = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            トリガーが実行されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerRun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.#ctor" />
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
            TriggerRun クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerRun (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string triggerRunId = null, string triggerName = null, string triggerType = null, Nullable&lt;DateTime&gt; triggerRunTimestamp = null, string status = null, string message = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,string&gt; triggeredPipelines = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string triggerRunId, string triggerName, string triggerType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; triggerRunTimestamp, string status, string message, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; triggeredPipelines) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional triggerRunId As String = null, Optional triggerName As String = null, Optional triggerType As String = null, Optional triggerRunTimestamp As Nullable(Of DateTime) = null, Optional status As String = null, Optional message As String = null, Optional properties As IDictionary(Of String, String) = null, Optional triggeredPipelines As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TriggerRun : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * string * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.TriggerRun" Usage="new Microsoft.Azure.Management.DataFactory.Models.TriggerRun (additionalProperties, triggerRunId, triggerName, triggerType, triggerRunTimestamp, status, message, properties, triggeredPipelines)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="triggerRunId" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="triggerType" Type="System.String" />
        <Parameter Name="triggerRunTimestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="triggeredPipelines" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="triggerRunId">トリガーの実行 id です。</param>
        <param name="triggerName">トリガーの名前です。</param>
        <param name="triggerType">トリガーの種類。</param>
        <param name="triggerRunTimestamp">実行の開始時刻をトリガーします。</param>
        <param name="status">トリガーの実行状態。 使用可能な値が含まれます: 'は Succeeded'、'失敗'、'処理中'</param>
        <param name="message">エラー メッセージをトリガーします。</param>
        <param name="properties">プロパティ名とトリガーの実行に関連する値の一覧です。 名前、値のペアは、トリガーの種類によって異なります。</param>
        <param name="triggeredPipelines">パイプラインの名前の一覧表示し、実行、トリガーによってトリガーされた Id を実行します。</param>
        <summary>
            TriggerRun クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、エラー メッセージをトリガーします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プロパティ名とトリガーの実行に関連する値の一覧を取得します。 名前、値のペアは、トリガーの種類によって異なります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得は、実行ステータスをトリガーします。 使用可能な値が含まれます: 'は Succeeded'、'失敗'、'処理中'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggeredPipelines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; TriggeredPipelines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; TriggeredPipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggeredPipelines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggeredPipelines As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.TriggeredPipelines : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggeredPipelines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggeredPipelines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パイプラインの名前と実行、トリガーによってトリガーされた実行の Id の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerName">
      <MemberSignature Language="C#" Value="public string TriggerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerName As String" />
      <MemberSignature Language="F#" Value="member this.TriggerName : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得には、名前がトリガーされます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerRunId">
      <MemberSignature Language="C#" Value="public string TriggerRunId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerRunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerRunId As String" />
      <MemberSignature Language="F#" Value="member this.TriggerRunId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerRunId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、実行 id をトリガーします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerRunTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TriggerRunTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TriggerRunTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerRunTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TriggerRunTimestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerRunTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerRunTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、実行の開始時刻をトリガーします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerType">
      <MemberSignature Language="C#" Value="public string TriggerType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerType As String" />
      <MemberSignature Language="F#" Value="member this.TriggerType : string" Usage="Microsoft.Azure.Management.DataFactory.Models.TriggerRun.TriggerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トリガーのタイプを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>