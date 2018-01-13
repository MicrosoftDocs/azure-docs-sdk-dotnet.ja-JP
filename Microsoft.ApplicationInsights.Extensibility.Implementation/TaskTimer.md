<Type Name="TaskTimer" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer">
  <TypeSignature Language="C#" Value="public class TaskTimer : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskTimer extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskTimer&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TaskTimer = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("This class will be removed in the next major version. Application Insights base library wouldn't provide this functionality any longer.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            遅延特定し、すべてのエラー ログに記録した後は、タスクを実行します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskTimer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public void Cancel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Cancel() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Cancel" />
      <MemberSignature Language="VB.NET" Value="Public Sub Cancel ()" />
      <MemberSignature Language="F#" Value="member this.Cancel : unit -&gt; unit" Usage="taskTimer.Cancel " />
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
            現在のタスクを取り消します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delay">
      <MemberSignature Language="C#" Value="public TimeSpan Delay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Delay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Delay" />
      <MemberSignature Language="VB.NET" Value="Public Property Delay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Delay : TimeSpan with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Delay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、タスクの開始前に遅延を設定します。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="taskTimer.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
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
            リリースでは、アンマネージし、必要に応じてマネージ リソース。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InfiniteTimeSpan">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan InfiniteTimeSpan;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan InfiniteTimeSpan" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.InfiniteTimeSpan" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly InfiniteTimeSpan As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable InfiniteTimeSpan : TimeSpan" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.InfiniteTimeSpan" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            無限の期間を表します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStarted">
      <MemberSignature Language="C#" Value="public bool IsStarted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsStarted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.IsStarted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsStarted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsStarted : bool" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.IsStarted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクが既に開始されているかどうかを示す値を示す値かどうか取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start (Func&lt;System.Threading.Tasks.Task&gt; elapsed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Start(class System.Func`1&lt;class System.Threading.Tasks.Task&gt; elapsed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Start(System.Func{System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start (elapsed As Func(Of Task))" />
      <MemberSignature Language="F#" Value="member this.Start : Func&lt;System.Threading.Tasks.Task&gt; -&gt; unit" Usage="taskTimer.Start elapsed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elapsed" Type="System.Func&lt;System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="elapsed">タスクを実行します。</param>
        <summary>
            タスクを開始します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>