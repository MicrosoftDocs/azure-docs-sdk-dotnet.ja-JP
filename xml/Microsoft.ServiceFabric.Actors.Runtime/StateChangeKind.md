<Type Name="StateChangeKind" FullName="Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind">
  <TypeSignature Language="C#" Value="public enum StateChangeKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StateChangeKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum StateChangeKind" />
  <TypeSignature Language="F#" Value="type StateChangeKind = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="048ab-101">表すアクターの状態変化のような状態に<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />一連のアクター状態の変更内容を保存します。</span><span class="sxs-lookup"><span data-stu-id="048ab-101">Represents the kind of state change for an actor state when <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" /> saves changes to a set of actor states.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="Add" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind Add = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.Add" />
      <MemberSignature Language="VB.NET" Value="Add" />
      <MemberSignature Language="F#" Value="Add = 1" Usage="Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.Add" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="048ab-102">状態は、追加する必要があります。</span><span class="sxs-lookup"><span data-stu-id="048ab-102">The state needs to be added.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="048ab-103">状態の変更はありません。</span><span class="sxs-lookup"><span data-stu-id="048ab-103">No change in state</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="Remove" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind Remove = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.Remove" />
      <MemberSignature Language="VB.NET" Value="Remove" />
      <MemberSignature Language="F#" Value="Remove = 3" Usage="Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.Remove" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="048ab-104">状態は、削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="048ab-104">The state needs to be removed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="Update" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind Update = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.Update" />
      <MemberSignature Language="VB.NET" Value="Update" />
      <MemberSignature Language="F#" Value="Update = 2" Usage="Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.Update" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="048ab-105">状態は、更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="048ab-105">The state needs to be updated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>