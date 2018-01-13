<Type Name="IWithPartitioning" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithPartitioning">
  <TypeSignature Language="C#" Value="public interface IWithPartitioning" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPartitioning" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithPartitioning" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPartitioning" />
  <TypeSignature Language="F#" Value="type IWithPartitioning = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            パーティション分割の動作を指定できるように、キューの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPartitioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithoutPartitioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithoutPartitioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithPartitioning.WithoutPartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPartitioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPartitioning : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithPartitioning.WithoutPartitioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既定のパーティション分割を無効にするこのキューでを指定します。
            注: Service Bus の親が Premium SKU の場合、パーティション無効にできません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPartitioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithPartitioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithPartitioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithPartitioning.WithPartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPartitioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPartitioning : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithPartitioning.WithPartitioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このキューでパーティション分割を有効することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>