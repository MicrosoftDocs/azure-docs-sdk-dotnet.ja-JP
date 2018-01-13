<Type Name="BatchClientBehavior" FullName="Microsoft.Azure.Batch.BatchClientBehavior">
  <TypeSignature Language="C#" Value="public abstract class BatchClientBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit BatchClientBehavior extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class BatchClientBehavior" />
  <TypeSignature Language="F#" Value="type BatchClientBehavior = class" />
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
            <span data-ttu-id="20954-101">派生クラスでは、Azure Batch サービスのクライアントのオペレーション動作を変更します。</span><span class="sxs-lookup"><span data-stu-id="20954-101">Derived classes modify operational behaviors of a Azure Batch Service client.</span></span>  <span data-ttu-id="20954-102">誤順序のと同時に複数のスレッドによって、派生クラスを呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="20954-102">Derived classes can be called out of order and simultaneously by several threads.</span></span>  <span data-ttu-id="20954-103">実装は、スレッド セーフにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="20954-103">Implementations should be threadsafe.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected BatchClientBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClientBehavior.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>