<Type Name="ITelemetry" FullName="Microsoft.ApplicationInsights.Channel.ITelemetry">
  <TypeSignature Language="C#" Value="public interface ITelemetry" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetry" />
  <TypeSignature Language="F#" Value="type ITelemetry = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Application insights の基本製品利用統計情報の種類。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この製品利用統計情報のインスタンスに関連付けられているコンテキストを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="iTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sanitize">
      <MemberSignature Language="C#" Value="public void Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize" />
      <MemberSignature Language="VB.NET" Value="Public Sub Sanitize ()" />
      <MemberSignature Language="F#" Value="abstract member Sanitize : unit -&gt; unit" Usage="iTelemetry.Sanitize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            機能では、配布ポイントの制約に基づく製品利用統計情報項目のプロパティです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または製品利用統計情報アイテムの絶対順序を定義する値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            シーケンスは、アップロードされるテレメトリのアイテムの絶対順序を追跡するために使用されます。 現在のブート セッションとアップロードのキューに追加された各イベントの識別子を増分するは安定した id を含む 2 部構成値である: これは 1 ずつ増分すべてのイベントのシステム全体の UTC です。
            永続化のためには、ホストのプロセスから生成されたすべてのイベントのインクリメントこれはします。    
            シーケンスは、追跡イベントの数が起動され、イベントの数がアップロードされたされ、アップロードと受信サーバー上のイベントの重複除去の間に失われるデータの識別を有効にします。
            <a href="https://microsoft.sharepoint.com/teams/CommonSchema/Shared%20Documents/Schema%20Specs/Common%20Schema%202%20-%20Language%20Specification.docx" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または日付と時刻の製品利用統計情報が記録されるタイミングを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>