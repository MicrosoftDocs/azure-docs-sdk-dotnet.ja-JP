<Type Name="SynchronousMethodExceptionBehavior" FullName="Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior">
  <TypeSignature Language="C#" Value="public class SynchronousMethodExceptionBehavior : Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SynchronousMethodExceptionBehavior extends Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Class SynchronousMethodExceptionBehavior&#xA;Inherits BatchClientBehavior" />
  <TypeSignature Language="F#" Value="type SynchronousMethodExceptionBehavior = class&#xA;    inherit BatchClientBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.BatchClientBehavior</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f0e1-101">A<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />同期メソッドから例外をスローする方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="9f0e1-101">A <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> which specifies how exceptions should be thrown from synchronous methods.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="9f0e1-102">既定では、同期メソッドは、非同期の同じ例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="9f0e1-102">By default, synchronous methods throw the same exceptions as asynchronous ones.</span></span>  <span data-ttu-id="9f0e1-103">Azure.Batch クライアント 4.0 より前のバージョンとの互換性を指定できます、<see cref="F:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior.ThrowAggregateException" />で同期メソッドからスローされる例外をラップする動作、<see cref="T:System.AggregateException" />です。</span><span class="sxs-lookup"><span data-stu-id="9f0e1-103">For compatability with versions of the Azure.Batch client prior to 4.0, you can specify the <see cref="F:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior.ThrowAggregateException" /> behavior to wrap exceptions thrown from synchronous methods in an <see cref="T:System.AggregateException" />.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ThrowAggregateException">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior ThrowAggregateException;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior ThrowAggregateException" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior.ThrowAggregateException" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ThrowAggregateException As SynchronousMethodExceptionBehavior " />
      <MemberSignature Language="F#" Value=" staticval mutable ThrowAggregateException : Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior" Usage="Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior.ThrowAggregateException" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f0e1-104">この動作により、同期メソッドをスローする<see cref="T:System.AggregateException" />エラー発生時にします。</span><span class="sxs-lookup"><span data-stu-id="9f0e1-104">This behavior causes synchronous methods to throw <see cref="T:System.AggregateException" /> on failure.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="9f0e1-105">これが既定値<see cref="T:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior" />Azure.Batch バージョン 4.0 より前で使用します。</span><span class="sxs-lookup"><span data-stu-id="9f0e1-105">This was the default <see cref="T:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior" /> used by Azure.Batch versions prior to 4.0.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>