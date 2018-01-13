<Type Name="PoolStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics">
  <TypeSignature Language="C#" Value="public class PoolStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolStatistics" />
  <TypeSignature Language="F#" Value="type PoolStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プールの有効期間の使用効率とリソース使用状況の統計を格納します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.#ctor" />
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
            PoolStatistics クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolStatistics (string url, DateTime startTime, DateTime lastUpdateTime, Microsoft.Azure.Batch.Protocol.Models.UsageStatistics usageStats = null, Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics resourceStats = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, class Microsoft.Azure.Batch.Protocol.Models.UsageStatistics usageStats, class Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics resourceStats) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.#ctor(System.String,System.DateTime,System.DateTime,Microsoft.Azure.Batch.Protocol.Models.UsageStatistics,Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, startTime As DateTime, lastUpdateTime As DateTime, Optional usageStats As UsageStatistics = null, Optional resourceStats As ResourceStatistics = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolStatistics : string * DateTime * DateTime * Microsoft.Azure.Batch.Protocol.Models.UsageStatistics * Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolStatistics (url, startTime, lastUpdateTime, usageStats, resourceStats)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="usageStats" Type="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics" />
        <Parameter Name="resourceStats" Type="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics" />
      </Parameters>
      <Docs>
        <param name="url">統計情報の URL です。</param>
        <param name="startTime">統計情報の時間範囲の開始時刻です。</param>
        <param name="lastUpdateTime">これで、統計の最終更新時刻。 すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。</param>
        <param name="usageStats">コア時間使用量など、プールの使用率に関連する統計。</param>
        <param name="resourceStats">プール内のコンピューティング ノードでリソースの消費量に関連する統計。</param>
        <summary>
            PoolStatistics クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定する、統計の最終更新時刻。
            すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceStats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics ResourceStats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics ResourceStats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.ResourceStats" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceStats As ResourceStatistics" />
      <MemberSignature Language="F#" Value="member this.ResourceStats : Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.ResourceStats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceStats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内のコンピューティング ノードでリソース消費量に関連する統計情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または統計の時間範囲の開始時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または統計情報の URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageStats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UsageStatistics UsageStats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UsageStatistics UsageStats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.UsageStats" />
      <MemberSignature Language="VB.NET" Value="Public Property UsageStats As UsageStatistics" />
      <MemberSignature Language="F#" Value="member this.UsageStats : Microsoft.Azure.Batch.Protocol.Models.UsageStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.UsageStats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usageStats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.UsageStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコア時間使用量など、プールの使用率に関連する統計情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolStatistics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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