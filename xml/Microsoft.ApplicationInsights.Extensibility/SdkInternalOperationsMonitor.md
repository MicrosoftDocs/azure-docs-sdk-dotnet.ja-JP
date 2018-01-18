<Type Name="SdkInternalOperationsMonitor" FullName="Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor">
  <TypeSignature Language="C#" Value="public static class SdkInternalOperationsMonitor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SdkInternalOperationsMonitor extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor" />
  <TypeSignature Language="VB.NET" Value="Public Class SdkInternalOperationsMonitor" />
  <TypeSignature Language="F#" Value="type SdkInternalOperationsMonitor = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2454c-101">スレッドが現時点で内部操作 SDK を実行しているかどうかを定義するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2454c-101">Helps to define whether thread is performing SDK internal operation at the moment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Enter">
      <MemberSignature Language="C#" Value="public static void Enter ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Enter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor.Enter" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Enter ()" />
      <MemberSignature Language="F#" Value="static member Enter : unit -&gt; unit" Usage="Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor.Enter " />
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
            <span data-ttu-id="2454c-102">内部操作を実行するとスレッドをマークします。</span><span class="sxs-lookup"><span data-stu-id="2454c-102">Marks the thread as executing the internal operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exit">
      <MemberSignature Language="C#" Value="public static void Exit ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Exit() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor.Exit" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Exit ()" />
      <MemberSignature Language="F#" Value="static member Exit : unit -&gt; unit" Usage="Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor.Exit " />
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
            <span data-ttu-id="2454c-103">内部操作を実行するとスレッドをマークします。</span><span class="sxs-lookup"><span data-stu-id="2454c-103">Unmarks the thread as executing the internal operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEntered">
      <MemberSignature Language="C#" Value="public static bool IsEntered ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsEntered() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor.IsEntered" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsEntered () As Boolean" />
      <MemberSignature Language="F#" Value="static member IsEntered : unit -&gt; bool" Usage="Microsoft.ApplicationInsights.Extensibility.SdkInternalOperationsMonitor.IsEntered " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2454c-104">決定するかどうか、現在のスレッドが内部操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="2454c-104">Determines whether the current thread executing the internal operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2454c-105">true の場合、現在のスレッドが内部の処理の実行それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="2454c-105">true if the current thread executing the internal operation; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>