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
            信頼できる方法のコレクションを指定します、ロック リソース、同時実行トランザクションによってリソースにアクセスできる方法を決定します。
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
            トランザクションの操作と分離レベルに基づく既定のロック モードを使用します。
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
            更新するためのものでは、リソースで使用されます。 一般的な形式の複数のトランザクションは、読み取り、ロック、および可能性のあるリソースを後で更新するときに発生するデッドロックを防ぎます。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>