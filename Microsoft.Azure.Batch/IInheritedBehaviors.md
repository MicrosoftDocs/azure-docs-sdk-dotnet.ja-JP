<Type Name="IInheritedBehaviors" FullName="Microsoft.Azure.Batch.IInheritedBehaviors">
  <TypeSignature Language="C#" Value="public interface IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="VB.NET" Value="Public Interface IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type IInheritedBehaviors = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f6c79-101">メソッドとインスタンス化する親オブジェクトから継承されているプロパティ。</span><span class="sxs-lookup"><span data-stu-id="f6c79-101">Methods and properties that are inherited from the instantiating parent object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6c79-102">インスタンス化またはインスタンス化する親オブジェクト (継承) からコピーして、このコレクションは最初に設定されます。</span><span class="sxs-lookup"><span data-stu-id="f6c79-102">This collection is initially populated by instantiation or by copying from the instantiating parent object (inheritance).</span></span>
            <span data-ttu-id="f6c79-103">このモデルでは、コレクションは、独立したが、メンバーは、共有された参照です。</span><span class="sxs-lookup"><span data-stu-id="f6c79-103">In this model, the collections are independent but the members are shared references.</span></span>
            <span data-ttu-id="f6c79-104">このコレクションのメンバーは、alter または Azure Batch サービス クライアント オブジェクトのさまざまな動作をカスタマイズします。</span><span class="sxs-lookup"><span data-stu-id="f6c79-104">Members of this collection alter or customize various behaviors of Azure Batch Service client objects.</span></span>
            <span data-ttu-id="f6c79-105">これらの動作は、子クラス インスタンスをすべてによって一般に継承されます。</span><span class="sxs-lookup"><span data-stu-id="f6c79-105">These behaviors are generally inherited by any child class instances.</span></span>  
            <span data-ttu-id="f6c79-106">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="f6c79-106">Modifications are applied in the order of the collection.</span></span>
            <span data-ttu-id="f6c79-107">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="f6c79-107">The last write wins.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>