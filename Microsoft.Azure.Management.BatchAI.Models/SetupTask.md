<Type Name="SetupTask" FullName="Microsoft.Azure.Management.BatchAI.Models.SetupTask">
  <TypeSignature Language="C#" Value="public class SetupTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SetupTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.SetupTask" />
  <TypeSignature Language="VB.NET" Value="Public Class SetupTask" />
  <TypeSignature Language="F#" Value="type SetupTask = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスターのコンピューティング ノードをカスタマイズするために使用するセットアップ タスクを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SetupTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.SetupTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SetupTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SetupTask (string commandLine, string stdOutErrPathPrefix, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables = null, Nullable&lt;bool&gt; runElevated = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string stdOutErrPathPrefix, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables, valuetype System.Nullable`1&lt;bool&gt; runElevated) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.SetupTask.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (commandLine As String, stdOutErrPathPrefix As String, Optional environmentVariables As IList(Of EnvironmentSetting) = null, Optional runElevated As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.SetupTask : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.SetupTask" Usage="new Microsoft.Azure.Management.BatchAI.Models.SetupTask (commandLine, stdOutErrPathPrefix, environmentVariables, runElevated)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="stdOutErrPathPrefix" Type="System.String" />
        <Parameter Name="environmentVariables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt;" />
        <Parameter Name="runElevated" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine">コマンド ライン セットアップ プロセスを開始します。</param>
        <param name="stdOutErrPathPrefix">Stdout とセットアップ タスクの stderror のバッチ AI サービスのアップロード場所のパスです。</param>
        <param name="environmentVariables">環境設定のコレクション。</param>
        <param name="runElevated">セットアップ タスクを管理者特権モードで実行するかどうかを指定します。 既定値は false です。</param>
        <summary>
            SetupTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.SetupTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.SetupTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得または設定コマンド ライン セットアップ プロセスを開始します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentVariables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.SetupTask.EnvironmentVariables" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentVariables As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentVariables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.SetupTask.EnvironmentVariables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentVariables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または環境設定のコレクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunElevated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RunElevated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RunElevated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.SetupTask.RunElevated" />
      <MemberSignature Language="VB.NET" Value="Public Property RunElevated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RunElevated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.SetupTask.RunElevated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runElevated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、管理者特権モードでセットアップ タスクを実行するかどうかを指定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StdOutErrPathPrefix">
      <MemberSignature Language="C#" Value="public string StdOutErrPathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StdOutErrPathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.SetupTask.StdOutErrPathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property StdOutErrPathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.StdOutErrPathPrefix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.SetupTask.StdOutErrPathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stdOutErrPathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または stdout とセットアップ タスクの stderror のバッチ AI サービスのアップロード場所のパスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.SetupTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="setupTask.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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