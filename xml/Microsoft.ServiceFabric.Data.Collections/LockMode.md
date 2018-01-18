<Type Name="LockMode" FullName="Microsoft.ServiceFabric.Data.Collections.LockMode">
  <TypeSignature Language="C#" Value="public enum LockMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LockMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.LockMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum LockMode" />
  <TypeSignature Language="F#" Value="type LockMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="45404-101">信頼できる方法のコレクションを指定します、ロック リソース、同時実行トランザクションによってリソースにアクセスできる方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="45404-101">Specifies how reliable collections will lock resources, which determines how the resources can be accessed by concurrent transactions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.Collections.LockMode Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.Collections.LockMode.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="Microsoft.ServiceFabric.Data.Collections.LockMode.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Collections.LockMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="45404-102">トランザクションの操作と分離レベルに基づく既定のロック モードを使用します。</span><span class="sxs-lookup"><span data-stu-id="45404-102">Use the default lock mode based on the operation and isolation level of the transaction.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="Update" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.Collections.LockMode Update = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.Collections.LockMode.Update" />
      <MemberSignature Language="VB.NET" Value="Update" />
      <MemberSignature Language="F#" Value="Update = 1" Usage="Microsoft.ServiceFabric.Data.Collections.LockMode.Update" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Collections.LockMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="45404-103">更新するためのものでは、リソースで使用されます。</span><span class="sxs-lookup"><span data-stu-id="45404-103">Used on resources that are intended to be updated.</span></span> <span data-ttu-id="45404-104">一般的な形式の複数のトランザクションは、読み取り、ロック、および可能性のあるリソースを後で更新するときに発生するデッドロックを防ぎます。</span><span class="sxs-lookup"><span data-stu-id="45404-104">Prevents a common form of deadlock that occurs when multiple transactions are reading, locking, and potentially updating resources later.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>