<Type Name="ExitOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitOptions">
  <TypeSignature Language="C#" Value="public class ExitOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitOptions" />
  <TypeSignature Language="F#" Value="type ExitOptions = class" />
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
            バッチ サービスが特定の終了条件に応答する方法を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.#ctor" />
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
            ExitOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; jobAction = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; dependencyAction = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; jobAction, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; dependencyAction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobAction},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DependencyAction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional jobAction As Nullable(Of JobAction) = null, Optional dependencyAction As Nullable(Of DependencyAction) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitOptions : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitOptions (jobAction, dependencyAction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobAction" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt;" />
        <Parameter Name="dependencyAction" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt;" />
      </Parameters>
      <Docs>
        <param name="jobAction">指定された終了条件と、ジョブの onTaskFailed プロパティで、タスクが完了した場合、タスクを含む、ジョブで実行するアクションは、'performExitOptionsJobAction' です。</param>
        <param name="dependencyAction">バッチ サービスがこのタスクに依存しているタスクを実行するアクション。</param>
        <summary>
            ExitOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependencyAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; DependencyAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; DependencyAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.DependencyAction" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyAction As Nullable(Of DependencyAction)" />
      <MemberSignature Language="F#" Value="member this.DependencyAction : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitOptions.DependencyAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependencyAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ サービスがこのタスクに依存しているタスクを実行するアクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定では終了コード 0、およびその他のすべての終了条件には、' block' の '満たす' です。 DependencyAction プロパティを指定して、false がエラーを返します。 ジョブの usesTaskDependencies プロパティに設定されている場合と、追加のタスクの要求はエラーで失敗無効なプロパティ値です。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。 使用可能な値が含まれます: 'を満たす'、'を ' ブロック
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; JobAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; JobAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.JobAction" />
      <MemberSignature Language="VB.NET" Value="Public Property JobAction As Nullable(Of JobAction)" />
      <MemberSignature Language="F#" Value="member this.JobAction : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitOptions.JobAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定された終了条件を満たすタスクが完了したプロパティは、ジョブの onTaskFailed 'performExitOptionsJobAction' 場合に、タスクを含むジョブを実行するアクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は none 終了コード 0 を他のすべての終了条件を終了します。 ジョブの onTaskFailed プロパティが noAction の場合は、エラーを返します、このプロパティを指定して、追加のタスクの要求はエラーで失敗無効なプロパティ値です。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。 使用可能な値が含まれます 'none'、'disable'、'終了'。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>