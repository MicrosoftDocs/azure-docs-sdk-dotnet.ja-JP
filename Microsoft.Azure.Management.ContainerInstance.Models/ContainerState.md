<Type Name="ContainerState" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ContainerState">
  <TypeSignature Language="C#" Value="public class ContainerState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerState extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerState" />
  <TypeSignature Language="F#" Value="type ContainerState = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コンテナー インスタンスの状態。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ContainerState クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerState (string state = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;int&gt; exitCode = null, Nullable&lt;DateTime&gt; finishTime = null, string detailStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; finishTime, string detailStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional state As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional finishTime As Nullable(Of DateTime) = null, Optional detailStatus As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerState : string * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerState" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerState (state, startTime, exitCode, finishTime, detailStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="finishTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="detailStatus" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state">コンテナーのインスタンスの状態。</param>
        <param name="startTime">コンテナーのインスタンスの状態が開始されたときに日付/時刻。</param>
        <param name="exitCode">コンテナー インスタンス終了コードを使用すると、対応してから、`docker run`コマンド。</param>
        <param name="finishTime">コンテナーのインスタンスの状態が終了したときに日付と時刻。</param>
        <param name="detailStatus">コンテナーのインスタンスの状態の人間が判読できる状態です。</param>
        <summary>
            ContainerState クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailStatus">
      <MemberSignature Language="C#" Value="public string DetailStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DetailStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.DetailStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailStatus As String" />
      <MemberSignature Language="F#" Value="member this.DetailStatus : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.DetailStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="detailStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー インスタンスの状態の人間が判読できる状態に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の対応するコンテナー インスタンスの終了コード、`docker run`コマンド。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FinishTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FinishTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FinishTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.FinishTime" />
      <MemberSignature Language="VB.NET" Value="Public Property FinishTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FinishTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.FinishTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="finishTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー インスタンスの状態が終了したときに日付と時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー インスタンスの状態が開始されたときに日付と時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerState.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー インスタンスの状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>