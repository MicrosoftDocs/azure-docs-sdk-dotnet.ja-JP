<Type Name="TestCommandProgress" FullName="System.Fabric.TestCommandProgress">
  <TypeSignature Language="C#" Value="public abstract class TestCommandProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TestCommandProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TestCommandProgress" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TestCommandProgress" />
  <TypeSignature Language="F#" Value="type TestCommandProgress = class" />
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
            <span data-ttu-id="b05d6-101">進行中のオブジェクトの基本クラス。</span><span class="sxs-lookup"><span data-stu-id="b05d6-101">Base class for the progress objects.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="b05d6-102">このクラスは、TestCommandProgressState を返します</span><span class="sxs-lookup"><span data-stu-id="b05d6-102">This class returns the TestCommandProgressState</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal TestCommandProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TestCommandProgress.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b05d6-103">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="b05d6-103">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public System.Fabric.TestCommandProgressState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TestCommandProgressState State" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TestCommandProgress.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As TestCommandProgressState" />
      <MemberSignature Language="F#" Value="member this.State : System.Fabric.TestCommandProgressState" Usage="System.Fabric.TestCommandProgress.State" />
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
            <span data-ttu-id="b05d6-104">これで、アクションが状態を取得します実行中、Completed、Faulted、または無効です。</span><span class="sxs-lookup"><span data-stu-id="b05d6-104">Gets the State at which the action is now: Running, Completed, Faulted, or Invalid</span></span>
            </summary>
        <value><span data-ttu-id="b05d6-105">テスト コマンドの状態。</span><span class="sxs-lookup"><span data-stu-id="b05d6-105">The state of the test command.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TestCommandProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="testCommandProgress.ToString " />
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
            <span data-ttu-id="b05d6-106">状態の文字列表現を返します</span><span class="sxs-lookup"><span data-stu-id="b05d6-106">Returns the string representation of the State</span></span>
            </summary>
        <returns><span data-ttu-id="b05d6-107">状態の文字列表現</span><span class="sxs-lookup"><span data-stu-id="b05d6-107">String representation of the State</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>