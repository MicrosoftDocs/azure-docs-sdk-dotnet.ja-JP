<Type Name="Schedule" FullName="Microsoft.Azure.Batch.Protocol.Models.Schedule">
  <TypeSignature Language="C#" Value="public class Schedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Schedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.Schedule" />
  <TypeSignature Language="VB.NET" Value="Public Class Schedule" />
  <TypeSignature Language="F#" Value="type Schedule = class" />
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
            これに基づいてジョブを作成するスケジュール
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Schedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Schedule.#ctor" />
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
            スケジュール クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Schedule (Nullable&lt;DateTime&gt; doNotRunUntil = null, Nullable&lt;DateTime&gt; doNotRunAfter = null, Nullable&lt;TimeSpan&gt; startWindow = null, Nullable&lt;TimeSpan&gt; recurrenceInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; doNotRunUntil, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; doNotRunAfter, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; startWindow, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; recurrenceInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Schedule.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional doNotRunUntil As Nullable(Of DateTime) = null, Optional doNotRunAfter As Nullable(Of DateTime) = null, Optional startWindow As Nullable(Of TimeSpan) = null, Optional recurrenceInterval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.Schedule : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.Schedule" Usage="new Microsoft.Azure.Batch.Protocol.Models.Schedule (doNotRunUntil, doNotRunAfter, startWindow, recurrenceInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="doNotRunUntil" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="doNotRunAfter" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="startWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="recurrenceInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="doNotRunUntil">最も早い時刻を下にあるこのジョブ スケジュールを任意のジョブが作成されます。</param>
        <param name="doNotRunAfter">までジョブは作成されません下にあるこのジョブ スケジュールの時刻。 スケジュールは、この期限を過ぎると、このジョブ スケジュール の下にアクティブなジョブがないとすぐに完了した状態に移行されます。</param>
        <param name="startWindow">時間間隔には、ジョブがスケジュールに示されて時から必要があります内に作成、ジョブを作成する必要があります。</param>
        <param name="recurrenceInterval">ジョブ スケジュール の下の 2 つの連続するジョブの開始時刻の時間間隔。 ジョブのスケジュールは、特定の時点で最大でその下にある 1 つのアクティブなジョブを持つことができます。</param>
        <summary>
            スケジュール クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunAfter As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunAfter : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="doNotRunAfter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するまでジョブは作成されません下にあるこのジョブ スケジュールした時刻。 スケジュールは、この期限を過ぎると、このジョブ スケジュール の下にアクティブなジョブがないとすぐに完了した状態に移行されます。
            </summary>
        <value>To be added.</value>
        <remarks>
            DoNotRunAfter 時刻を指定しないし、定期的なジョブ スケジュールを作成するの場合は、明示的に終了するまで、ジョブ スケジュールがアクティブな残ります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunUntil">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunUntil { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunUntil" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunUntil" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunUntil As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunUntil : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunUntil" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="doNotRunUntil")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または下にあるこのジョブ スケジュールを任意のジョブが作成されます最も早い時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            DoNotRunUntil 時間を指定しない場合、スケジュールがジョブをすぐに作成する準備ができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RecurrenceInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RecurrenceInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.RecurrenceInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RecurrenceInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.RecurrenceInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブ スケジュール の下の 2 つの連続するジョブの開始時刻の時間間隔を設定します。 ジョブのスケジュールは、特定の時点で最大でその下にある 1 つのアクティブなジョブを持つことができます。
            </summary>
        <value>To be added.</value>
        <remarks>
            ジョブのスケジュールを持てないため最大でその下にある 1 つのアクティブなジョブ任意の時点でジョブのスケジュールでは、新しいジョブを作成するときは、前のジョブがまだ実行されている場合、Batch service はジョブを作成できません新しい、前のジョブが終了するまでです。 前のジョブが新しい recurrenceInterval の startWindow 期間内で完了しなかった場合は、新しいジョブがその間隔でスケジュールいません。 定期的なジョブの場合は、通常、jobSpecification で、jobManagerTask を指定してください。 JobManagerTask を使用しない場合、外部プロセスが監視ジョブを作成すると、ジョブにタスクを追加およびジョブの次回の定期実行の準備ができてを終了する必要があります。 既定値は、スケジュールが再発しない: doNotRunUntil 時刻より後の startWindow 内で、1 つのジョブが作成され、そのジョブが終了するとすぐには、スケジュールが完了しました。 最小値は、1 分です。 下限値を指定すると場合、Batch service はエラー; を使ってスケジュールを拒否します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StartWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StartWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.StartWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property StartWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.StartWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケジュールが、ジョブを作成する必要があります内で、ジョブを作成する必要がありますを示す時からの時間間隔を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ジョブは、startWindow 間隔内で作成されていない場合、'営業案件' は失われます。スケジュールの次の反復までジョブは作成されません。 スケジュールが反復的な startWindow は、定期実行期間より長い場合は、し、これは、無限の startWindow と同等、次回の定期的なアイテムに '' 期限切れになる 1 つ recurrenceInterval られているジョブはフォワード実行されないためです。 既定値は無限です。 最小値は、1 分です。 下限値を指定すると場合、Batch service はエラー; を使ってスケジュールを拒否します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>