<Type Name="StartTask" FullName="Microsoft.Azure.Management.Batch.Models.StartTask">
  <TypeSignature Language="C#" Value="public class StartTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.StartTask" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTask" />
  <TypeSignature Language="F#" Value="type StartTask = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コンピューティング ノードがプールを Azure Batch サービスを参加させるときや、コンピューティング ノードが再起動または再イメージ化されるときに実行されるタスクです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.StartTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StartTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask (string commandLine = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Management.Batch.Models.UserIdentity userIdentity = null, Nullable&lt;int&gt; maxTaskRetryCount = null, Nullable&lt;bool&gt; waitForSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Management.Batch.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.StartTask.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.EnvironmentSetting},Microsoft.Azure.Management.Batch.Models.UserIdentity,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.StartTask : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; * Microsoft.Azure.Management.Batch.Models.UserIdentity * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Batch.Models.StartTask" Usage="new Microsoft.Azure.Management.Batch.Models.StartTask (commandLine, resourceFiles, environmentSettings, userIdentity, maxTaskRetryCount, waitForSuccess)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Management.Batch.Models.UserIdentity" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine">開始タスクのコマンドラインです。</param>
        <param name="resourceFiles">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</param>
        <param name="environmentSettings">開始タスクの環境変数設定の一覧。</param>
        <param name="userIdentity">開始タスクを実行するユーザー id。</param>
        <param name="maxTaskRetryCount">タスクを再試行できる最大回数。</param>
        <param name="waitForSuccess">バッチ サービスは、開始タスクが正常に完了待機する必要があるかどうか (つまり、終了コード 0 で終了する)、コンピューティング ノード上のすべてのタスクをスケジュールする前にします。</param>
        <summary>
            StartTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または開始タスクのコマンドラインを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。 このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。
            StartTask の他のプロパティを指定するかどうかは必須。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または開始タスクの環境変数設定の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、タスクが再試行される最大回数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。 この値によって再試行の回数が限定されますのでご注意ください。 Batch サービスはタスクを 1 回試行してから、上限に達するまで再試行できます。 たとえば、最大再試行回数が 3 の場合は、バッチを試みるタスクには最大 4 倍 (最初の試行が 1 回と 3 回)。 最大再試行回数が 0 の場合、Batch service は、タスクを再試行しません。 最大再試行回数場合は-1、バッチ サービスの再試行制限がないタスクです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Management.Batch.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userIdentity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または開始タスクを実行するユーザー id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitForSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、バッチ サービスは、開始タスクが正常に完了を待つ必要があるかどうか (つまり、終了コード 0 で終了する)、コンピューティング ノード上のすべてのタスクをスケジュールする前にします。
            </summary>
        <value>To be added.</value>
        <remarks>
            True で、開始タスクは、コンピューティング ノードで失敗した場合、バッチ サービスは、その最大再試行回数 (maxTaskRetryCount) まで開始タスクを再試行します。 タスクしている場合もない正常に完了し、すべての再試行、バッチ サービス マークした後、コンピューティング ノードを使用できない場合にタスクのスケジュールがありません。 この条件は、ノードの状態とスケジュール エラーの詳細を使用して検出できます。 False の場合、バッチ サービスは、開始タスクの完了を待機しません。 この例では、その他のタスクが、開始タスクがまだ実行されているコンピューティング ノードで実行されているを開始することができます。され、開始タスクが失敗した場合でも新しいタスクがノードにあるスケジュール続行されます。 既定値は false です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>