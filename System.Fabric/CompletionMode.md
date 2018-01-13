<Type Name="CompletionMode" FullName="System.Fabric.CompletionMode">
  <TypeSignature Language="C#" Value="public enum CompletionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed CompletionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CompletionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum CompletionMode" />
  <TypeSignature Language="F#" Value="type CompletionMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            これは、API が完了する必要がありますを示すために使用される列挙型です。 
            </summary>
    <remarks>
            値は、操作の要求が行われるとき、または要求された操作が完了したときに、API が完了する必要があるかどうかを示します。 たとえば、ノードを再起動する要求をすぐに、要求が承諾されると、または API では、ノードが再起動されることを確認できます完了でした。 実際の認証は、使用されている API に依存します。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="DoNotVerify">
      <MemberSignature Language="C#" Value="DoNotVerify" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode DoNotVerify = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.DoNotVerify" />
      <MemberSignature Language="VB.NET" Value="DoNotVerify" />
      <MemberSignature Language="F#" Value="DoNotVerify = 1" Usage="System.Fabric.CompletionMode.DoNotVerify" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            アクションの完了を確認しません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.CompletionMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            入力候補モードでは、有効な値はありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="Verify" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode Verify = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.Verify" />
      <MemberSignature Language="VB.NET" Value="Verify" />
      <MemberSignature Language="F#" Value="Verify = 2" Usage="System.Fabric.CompletionMode.Verify" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            アクションの完了を確認します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>