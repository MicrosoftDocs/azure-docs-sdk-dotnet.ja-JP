<Type Name="TestCommandStatus" FullName="System.Fabric.Query.TestCommandStatus">
  <TypeSignature Language="C#" Value="public sealed class TestCommandStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TestCommandStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.TestCommandStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TestCommandStatus" />
  <TypeSignature Language="F#" Value="type TestCommandStatus = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスは、テスト コマンドの状態を表します。  呼び出す<see cref="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />IList この型のオブジェクトを返します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public Guid OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid OperationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.TestCommandStatus.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As Guid" />
      <MemberSignature Language="F#" Value="member this.OperationId : Guid" Usage="System.Fabric.Query.TestCommandStatus.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テスト コマンドの操作 Id。  この Guid は、テスト操作を開始するときに、ユーザーが提供されました。
            </summary>
        <value>OperationId を表す Guid です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public System.Fabric.TestCommandProgressState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TestCommandProgressState State" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.TestCommandStatus.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As TestCommandProgressState" />
      <MemberSignature Language="F#" Value="member this.State : System.Fabric.TestCommandProgressState" Usage="System.Fabric.Query.TestCommandStatus.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テスト コマンドの現在の状態。
            </summary>
        <value>現在の状態と TestCommandProgressState です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestCommandType">
      <MemberSignature Language="C#" Value="public System.Fabric.TestCommandType TestCommandType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TestCommandType TestCommandType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.TestCommandStatus.TestCommandType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TestCommandType As TestCommandType" />
      <MemberSignature Language="F#" Value="member this.TestCommandType : System.Fabric.TestCommandType" Usage="System.Fabric.Query.TestCommandStatus.TestCommandType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テスト コマンドの種類。
            </summary>
        <value>TestCommandType オブジェクトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.TestCommandStatus.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="testCommandStatus.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            OperationId、状態、および ActionType を文字列に書式設定します。
            </summary>
        <returns>書式設定された文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>